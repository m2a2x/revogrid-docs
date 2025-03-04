[@revolist/revogrid](README.md) / [Components](Namespace.Components.md) / RevogrData

# Interface: RevogrData

This component is responsible for rendering data
Rows, columns, groups and cells

## Properties

| Property | Type | Description | Defined in |
| ------ | ------ | ------ | ------ |
| `additionalData` | `any` | Additional data to pass to renderer Used in plugins such as vue or react to pass root app entity to cells | [src/components.d.ts:302](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L302) |
| `colData` | [`Observable`](TypeAlias.Observable.md)\<[`DSourceState`](TypeAlias.DSourceState.md)\<[`ColumnRegular`](Interface.ColumnRegular.md), [`DimensionCols`](TypeAlias.DimensionCols.md)\>\> | Column source | [src/components.d.ts:306](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L306) |
| `colType` | [`DimensionCols`](TypeAlias.DimensionCols.md) \| `"rowHeaders"` | Column data type | [src/components.d.ts:310](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L310) |
| `dataStore` | [`Observable`](TypeAlias.Observable.md)\<[`DSourceState`](TypeAlias.DSourceState.md)\<[`DataType`](TypeAlias.DataType.md), [`DimensionRows`](TypeAlias.DimensionRows.md)\>\> | Data rows source | [src/components.d.ts:314](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L314) |
| `dimensionRow` | [`Observable`](TypeAlias.Observable.md)\<[`DimensionSettingsState`](Interface.DimensionSettingsState.md)\> | Dimension settings Y | [src/components.d.ts:318](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L318) |
| `jobsBeforeRender` | `Promise`\<`any`\>[] | Prevent rendering until job is done. Can be used for initial rendering performance improvement. When several plugins require initial rendering this will prevent double initial rendering. | [src/components.d.ts:322](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L322) |
| `range` | `boolean` | Range allowed | [src/components.d.ts:326](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L326) |
| `readonly` | `boolean` | Readonly mode | [src/components.d.ts:330](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L330) |
| `rowClass` | `string` | Defines property from which to read row class | [src/components.d.ts:334](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L334) |
| `rowSelectionStore` | [`Observable`](TypeAlias.Observable.md)\<[`SelectionStoreState`](TypeAlias.SelectionStoreState.md)\> | Selection, range, focus for row selection | [src/components.d.ts:338](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L338) |
| `type` | [`DimensionRows`](TypeAlias.DimensionRows.md) | Row data type | [src/components.d.ts:342](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L342) |
| `updateCell` | (`e`: \{ `col`: `number`; `row`: `number`; \}) => `Promise`\<`void`\> | Pointed cell update. | [src/components.d.ts:346](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L346) |
| `viewportCol` | [`Observable`](TypeAlias.Observable.md)\<[`ViewportState`](Interface.ViewportState.md)\> | Viewport X | [src/components.d.ts:350](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L350) |
| `viewportRow` | [`Observable`](TypeAlias.Observable.md)\<[`ViewportState`](Interface.ViewportState.md)\> | Viewport Y | [src/components.d.ts:354](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/components.d.ts#L354) |
