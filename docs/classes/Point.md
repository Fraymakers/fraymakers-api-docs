---
layout: page
title: Point
---

## Static Functions

| Function Name | Description |
| --------------- | ------------- |
| create(x?:Float, y?:Float):Point |  |
| interpolate(point1:Point, point2:Point, fraction:Float):Point |  |
| lineSegmentsIntersect(a0:Point, a1:Point, b0:Point, b1:Point, out?:Point):Point | Gets the interesection between two line segments (or null if no intersection can be found)<br>Parameters:<br>- **a0** - First point of line segment A<br>- **a1** - Second point of line segment A<br>- **b0** - First point of line segment B<br>- **b1** - Second point of line segment B<br>- **out** - An existing point object to be used as a return value instead of allocating a new Point. |
| polar(len:Float, angle:Float, outPoint?:Point):Point |  |


## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| stable | Bool | `false` |  |
| x | Float | `n/a` |  |
| y | Float | `n/a` |  |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| add(other:TPoint):TPoint | Adds other into this point, returns this<br>Parameters:<br>- **other** - The other point to add |
| clone():TPoint |  |
| copyFrom(point:TPoint):Void |  |
| dispose():Void |  |
| distance(point:TPoint):Float |  |
| distanceSquared(point:TPoint):Float | Fast relative distance calculator |
| equals(point:TPoint):Bool |  |
| init(x?:Float, y?:Float):TPoint |  |
| offset(x:Float, y:Float):Void |  |
| scale(x:Float, y:Float):Void |  |


