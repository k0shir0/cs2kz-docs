# Measurements

Use `!measure` to measure the distance between two points on solid surfaces.

1. Aim at the first point and type `!measure` in chat to set the start position.
2. Aim at the second point and type `!measure` again to display the result.

Both points must be on solid surfaces. The first point expires after 60 seconds.

## Reading the result

For example, two points separated by 100 units along X, 50 units along Y, and no height difference produce:

```text
Distance - Horizontal: 111.8 (102.3), X: 100.0, Y: 50.0, Vertical: 0.0
```

| Field | Meaning |
| --- | --- |
| Horizontal | Distance between the points in the horizontal plane. |
| Value in parentheses | Minimum equivalent jumpstat distance between the points, accounting for the player's collision hull. |
| X / Y | Absolute distances along the map's world X and Y axes, independent of the direction you are facing. |
| Vertical | Signed height difference from the first point to the second: positive when the second point is higher, negative when it is lower. |

Reversing the points keeps the horizontal distance, effective jump distance, and X/Y distances the same, while reversing the sign of the vertical offset.

## Block measurements

Aim at one of two parallel, facing block surfaces and use `!measureblock` to measure the horizontal gap between them. The block result is rounded to a whole unit.
