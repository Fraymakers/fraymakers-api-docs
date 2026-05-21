---
layout: page
title: CharacterAiScript
---

## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| addInputOverrides(inputList:Array<Int>):Void |  |
| clearInputOverrides():Void |  |
| disableAction(action:Int):Void | Disables an action for use by the built-in AI<br> <br> @see CharacterAiActions |
| enableAction(action:Int):Void | Enables an action for use by the built-in AI<br> @see CharacterAiActions<br>Parameters:<br>- **action** - the action to enable |
| getImmediateTarget():Entity |  |
| getTargetFoe():Entity |  |
| hasInputOverrides():Bool |  |
| isActionEnabled(action:Int):Bool | Returns true of the given action is enabled<br> @see CharacterAiActions |
| isNoGroundBeneath(xOffset?:Float, threshold?:Float):Bool |  |
| isRecovering():Bool |  |
| toggleAction(action:Int, value:Bool):Void | Toggles an action's use by the built-in AI<br> @see CharacterAiActions<br>Parameters:<br>- **action** - the action to enable<br>- **value** - if true the action will be enabled, otherwise will be disabled |


