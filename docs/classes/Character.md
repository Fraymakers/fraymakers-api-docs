---
layout: page
title: Character
---

## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| attachToLedge(forceBodyLock?:Bool):Void |  |
| attemptLedgeGrab():Bool | Initiates a ledge-grab flow, which may or may not result in the character grabbing a ledge<br> |
| checkZeroToDeath(foe:Character, damageThreshold?:Int):Bool | Check if eligible for zero-to-death<br> <br> <br>Parameters:<br>- **damageThreshold** - threshold damage required to be considered a zero-to-death |
| clearInputBuffer():Void |  |
| endAnimation():Void |  |
| getAirdashCount():Int |  |
| getAssistCharge():Float |  |
| getAssistContentStat(name:String):Dynamic |  |
| getAssistController():AssistController |  |
| getAssistName():String |  |
| getCharacterStat(name:String):Dynamic |  |
| getDamageCounterAssistSprite():Sprite |  |
| getDoubleJumpCount():Int |  |
| getFoes():Array<Character> |  |
| getHeldControls():ControlsObject | Returns the held controls for the character. This data may be modified by the input buffer or other input post-processing. |
| getLives():Int |  |
| getPlayerConfig():PlayerConfig |  |
| getPortColor():Int | Returns color of the player's port. Returns cpuColor if character is CPU. |
| getPressedControls():ControlsObject | Returns the pressed controls for the character. This data may be modified by the input buffer or other input post-processing. |
| getRawHeldControls():ControlsObject | Returns the raw held controls for the character. This data is not modified by the input buffer or any other input post-processing. |
| getScore():Score |  |
| getType():Int |  |
| inAerialAttackState():Bool |  |
| inAirdashCanceledAnimation():Bool |  |
| inBufferInputState():Bool | Helper for determining if the character is in a state that should cause inputs to be buffered. This includes some non-state related conditions like being in hitstop or shieldstun. |
| inHurtState():Bool |  |
| inSpecialAttackState():Bool |  |
| inStrongAttackChargeState():Bool |  |
| isBufferInputState(state:Int):Bool | Helper for checking if a state is valid state for inputs to be buffered. |
| isFirstInputUpdate():Bool | Returns true during inputUpdateHook() execution if this is the first input update check for the character on the current frame. Note that when transitioning between states there is the possibilty of multiple input update checks in a single frame due to the input buffer. |
| isForcedGetup():Bool |  |
| performHitstopNudge(up:Bool, down:Bool, left:Bool, right:Bool, nudgeMultiplier:Float):Void |  |
| playAttackVoice():Void |  |
| playHurtHeavyVoice():Void |  |
| playHurtLightVoice():Void |  |
| playHurtMediumVoice():Void |  |
| playKoVoice():Void |  |
| preLand(effect?:Bool):Void | This function does the necessary functions pre-landing like resetting your jumps, disabling your fastfall, etc.<br> Note that running this function by itself will not actually put you in a landing animation necessarily.<br> Also note that this function runs automatically when calling toLand() |
| pressedStrongAttack():Int | Checks if character has made the necessary inputs for a STRONG.<br> <br> Use StrongInputType to check return values |
| releaseLedge():Void |  |
| setAirdashCount(count:Int):Int |  |
| setAssistCharge(value:Float):Void |  |
| setAssistCutinAnimation(animation:String):Void |  |
| setDoubleJumpCount(count:Int):Int |  |
| setLives(lives:Int):Void |  |
| updateAnimationStats(stats:Dynamic):Void |  |
| updateCharacterStats(stats:CharacterStatsProps):Void |  |


