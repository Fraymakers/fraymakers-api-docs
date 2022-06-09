---
layout: page
title: ControlsObject
---

Helper class for managing controls inputs

## Static Functions

| Function Name | Description |
| --------------- | ------------- |
| determinePressedControls(previousControls:Int, currentControls:Int):Int | Figures out which buttons were pressed VS held provided the previous and current control bits<br>Parameters:<br>- **previousControls** - Bits for the previous buttons<br>- **currentControls** - Bits for the current buttons |


## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| ACTION | Bool | `n/a` |  |
| ATTACK | Bool | `n/a` |  |
| CROUCH | Bool | `n/a` |  |
| DASH | Bool | `n/a` |  |
| DOWN | Bool | `n/a` |  |
| DROP_THROUGH | Bool | `n/a` |  |
| EMOTE | Bool | `n/a` |  |
| FULL_HOP | Bool | `n/a` |  |
| GRAB | Bool | `n/a` |  |
| JUMP | Bool | `n/a` |  |
| JUMP_ANY | Bool | `n/a` |  |
| LEFT | Bool | `n/a` |  |
| PAUSE | Bool | `n/a` |  |
| RIGHT | Bool | `n/a` |  |
| RIGHT_STICK_DOWN | Bool | `n/a` |  |
| RIGHT_STICK_LEFT | Bool | `n/a` |  |
| RIGHT_STICK_RIGHT | Bool | `n/a` |  |
| RIGHT_STICK_UP | Bool | `n/a` |  |
| SHIELD | Bool | `n/a` |  |
| SHIELD_AIR | Bool | `n/a` |  |
| SHORT_HOP | Bool | `n/a` |  |
| SPECIAL | Bool | `n/a` |  |
| STRONG | Bool | `n/a` |  |
| TAP_JUMP | Bool | `n/a` |  |
| TILT | Bool | `n/a` |  |
| UP | Bool | `n/a` |  |
| buttons | Int | `n/a` | Current state of button inputs represented by a 32-bit integer |
| flags | Int | `n/a` | Current state of input flags represented by a 32-bit integer |
| leftStickAngle | Float | `n/a` | Angle of the left stick calculated using leftStickX and leftStickY |
| leftStickAxes | Int | `n/a` |  |
| leftStickX | Float | `n/a` |  |
| leftStickY | Float | `n/a` |  |
| rightStickAngle | Float | `n/a` | Angle of the right stick calculated using leftStickX and leftStickY |
| rightStickAxes | Int | `n/a` |  |
| rightStickX | Float | `n/a` |  |
| rightStickY | Float | `n/a` |  |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| clone():ControlsObject |  |
| copyFrom(controlsObject:ControlsObject):Void | Copies the controls values from another ControlsObject instance<br>Parameters:<br>- **controlsObject** - The ControlsObject instance to copy controls data from |
| getAngle(rightStick?:Bool):Float | Returns the angle of the left stick or right sticks, rounded to the nearest 45 degree angle<br>Parameters:<br>- **rightStick** - Pass as true to use the right stick for the angle calculation. Otherwise the left stick is used. |
| hasRightStickAttackFlag():Bool |  |
| hasRightStickSpecialFlag():Bool |  |
| reset():Void |  |
| rightStickPressed():Bool |  |
| syncStickAngles():Void |  |
| toString():String | Returns a user readable string of current inputs |


