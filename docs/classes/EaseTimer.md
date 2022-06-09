---
layout: page
title: EaseTimer
---

## Static Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| EASE_IN_CUBIC | Int | `n/a` |  |
| EASE_IN_OUT_CUBIC | Int | `n/a` |  |
| EASE_IN_OUT_QUAD | Int | `n/a` |  |
| EASE_IN_OUT_QUART | Int | `n/a` |  |
| EASE_IN_OUT_QUINT | Int | `n/a` |  |
| EASE_IN_QUAD | Int | `n/a` |  |
| EASE_IN_QUART | Int | `n/a` |  |
| EASE_IN_QUINT | Int | `n/a` |  |
| EASE_OUT_CUBIC | Int | `n/a` |  |
| EASE_OUT_QUAD | Int | `n/a` |  |
| EASE_OUT_QUART | Int | `n/a` |  |
| EASE_OUT_QUINT | Int | `n/a` |  |
| LINEAR | Int | `n/a` |  |


## Static Functions

| Function Name | Description |
| --------------- | ------------- |
| constToString(value:Int):String | Translates constant to a user-readable string. |
| create(from:Float, to:Float, length:Int, easeType?:Int):EaseTimer |  |
| interpolate(from:Float, to:Float, t:Float, easeType?:Int):Float |  |


## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| value | Float | `n/a` |  |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| isCompleted():Bool |  |
| reset():Void |  |
| update():Void |  |


