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
| getAssistName():String |  |
| getCharacterStat(name:String):Dynamic |  |
| getDamageCounterAssistSprite():Sprite |  |
| getDoubleJumpCount():Int |  |
| getFoes():Array<Character> |  |
| getHeldControls():ControlsObject |  |
| getLives():Int |  |
| getPlayerConfig():PlayerConfig |  |
| getPortColor():Int | Returns color of the player's port. Returns cpuColor if character is CPU. |
| getPressedControls():ControlsObject |  |
| getScore():Score |  |
| getType():Int |  |
| inAerialAttackState():Bool |  |
| inAirdashCanceledAnimation():Bool |  |
| inHurtState():Bool |  |
| inSpecialAttackState():Bool |  |
| inStrongAttackChargeState():Bool |  |
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
| setDoubleJumpCount(count:Int):Int |  |
| setLives(lives:Int):Void |  |
| updateAnimationStats(stats:Dynamic):Void |  |
| updateCharacterStats(stats:CharacterStatsProps):Void |  |


