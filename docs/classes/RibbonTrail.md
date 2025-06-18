---
layout: page
title: RibbonTrail
---

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| alphaRatio | Float | `n/a` |  |
| heightScale | Float | `n/a` |  |
| movingRatio | Float | `n/a` |  |
| points | Array<TPoint> | `n/a` |  |
| useAnchoredReveal | Bool | `n/a` | When in anchored reveal mode, the ribbon is incrementally revealed based on the number of segments. <br> The reveal starts from the initial position, and continues as the position is updated.<br> Once the entire ribbon is visible, the entire trail moves along with the updated positions. |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| getPalette():Map<Int,Int> |  |
| setPalette(value:Map<Int,Int>):Map<Int,Int> |  |
| start(x:Float, y:Float):Void |  |
| stop():Void |  |
| updatePosition(x:Float, y:Float):Void |  |


