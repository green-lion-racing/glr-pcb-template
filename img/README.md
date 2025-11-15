# How to generate same orientated images

In KiCad 3D viewer enable **Raytracing**, **disable orthographic** projection.

## Orientation by selecting viewports

**For Front:** Select viewport named `Front` and export as back png.

**For Back:** Select viewport named `Back` and export as back png.

## Manual orientation

**For front:** Rotate 3x Clockwise X, Rotate 2x Counter Clockwise Z, Move up 1x and export as front png.

**Then for back:** Flip Board, Rotate 4x Counter Clockwise Z and export as back png.
