---
layout: page
title: CollisionBox
---

## Static Functions

| Function Name | Description |
| --------------- | ------------- |
| hitTestArray(arr1:Array<CollisionBox>, arr2:Array<CollisionBox>, selfLocation:TPoint, thatLocation:TPoint, selfScale:TPoint, thatScale:TPoint, selfRotation:Float, thatRotation:Float, selfPivot:TPoint, thatPivot:TPoint):Array<CollisionResult> |  |


## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| centerX | Float | `n/a` |  |
| centerY | Float | `n/a` |  |
| circular | Bool | `n/a` |  |
| depth | Float | `n/a` |  |
| flippedRect | Rectangle | `n/a` |  |
| height | Float | `n/a` |  |
| index | Int | `n/a` |  |
| metadata | Dynamic | `n/a` |  |
| name | String | `n/a` |  |
| pivotX | Float | `n/a` |  |
| pivotY | Float | `n/a` |  |
| rect | Rectangle | `n/a` |  |
| rotation | Float | `n/a` |  |
| type | Int | `n/a` |  |
| width | Float | `n/a` |  |
| x | Float | `n/a` |  |
| y | Float | `n/a` |  |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| clone():CollisionBox |  |
| copyFrom(collisionBox:CollisionBox):Void |  |
| equals(collisionBox:CollisionBox):Bool |  |
| hitTest(theirCollisionBox:CollisionBox, selfLocation:TPoint, thatLocation:TPoint, selfScale:TPoint, thatScale:TPoint, selfRotation:Float, thatRotation:Float, selfPivot:TPoint, thatPivot:TPoint):Rectangle | Compare hit boxes from self and the provided hit box |


