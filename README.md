# bs--01-bouncing-text

This project is an entry to my ["Baby-Steps"-project-series](https://www.game-object.de/projects)

## Description

A simple text bouncing of the edges of the screen.

## Ideas/Todos

The bouncing should be offset so the text wont cut off.

## Library Addings

Some Vector2D Math was added to calculate the position of the text.
- `Vector2D` with some math operations
- `Vector2DLike` an interface that can be accepted as a value
- `Rect` a rectangle representation with some overlap-checking methods
- `RectLike` an interface for a rectangle object
- `BoundingBox` another rect-interface using a different representation