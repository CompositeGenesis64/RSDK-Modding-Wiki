# SetTileLayerEntry

## Description
Sets the Chunk at `ChunkX`, `ChunkY` on tilelayer `Layer` to the index of `Value`.

## Parameters
- `Value`
The index value of the new chunk.
- `Layer`
The ID of the layer where the chunk comes from, valid values are:
    0(DEFORM_FG)
    1(DEFORM_FG_WATER)
    2(DEFORM_BG)
    3(DEFORM_BG_WATER)
- `ChunkX`
Position of the 128x128 chunk in the map on the horizontal axis.
- `ChunkY`
Position of the 128x128 chunk in the map on the vertical axis.

## Return Value
None.

## Syntax
```
SetTileLayerEntry(int Value, int Layer, int ChunkX, int ChunkY)
```

## Examples
```
SetTileLayerEntry(35, 0, 24, 96)
```