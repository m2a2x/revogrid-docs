[@revolist/revogrid](README.md) / ScrollCoordinateEvent

# Type Alias: ScrollCoordinateEvent

```ts
type ScrollCoordinateEvent: {
  coordinate: number;
  type: DimensionType;
};
```

Represents the event object that is emitted when scrolling occurs.
The `type` property indicates the type of dimension (row or column) being scrolled.
The `coordinate` property represents the current scroll position in that dimension.

## Type declaration

| Name | Type | Description | Defined in |
| ------ | ------ | ------ | ------ |
| `coordinate` | `number` | Represents the current scroll position in the specified dimension. The value is a number representing the coordinate in pixels. | [src/types/interfaces.ts:772](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/types/interfaces.ts#L772) |
| `type` | [`DimensionType`](TypeAlias.DimensionType.md) | Represents the type of dimension being scrolled. Possible values are 'rgRow' and 'rgCol'. | [src/types/interfaces.ts:766](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/types/interfaces.ts#L766) |

## Defined in

[src/types/interfaces.ts:761](https://github.com/revolist/revogrid/blob/39cfd614966a26ee6ce63b18984e6b24b2874cc5/src/types/interfaces.ts#L761)
