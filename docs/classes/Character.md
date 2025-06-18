---
layout: page
title: Character
---

## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| attachToLedge(forceBodyLock?:Bool):Void |  |
| attemptLedgeGrab():Bool | Initiates a ledge-grab flow, which may or may not result in the character grabbing a ledge<br> |
| attemptStructureLedgeGrab(structure:Structure, isLeftLedge:Bool):Bool | Initiates a ledge-grab flow on a particular structure, which may or may not result in the character grabbing a ledge.<br> <br> The character's state is not taken into account, only if the structure's ledge is available.<br>Parameters:<br>- **structure** - Structure to attempt to ledge-grab<br>- **isLeftLedge** - Bool True if the left ledge is to be grabbed, False if the right ledge is to be grabbed |
| checkZeroToDeath(foe:Character, damageThreshold?:Int):Bool | Check if eligible for zero-to-death<br> <br> <br>Parameters:<br>- **damageThreshold** - threshold damage required to be considered a zero-to-death |
| clearInputBuffer():Void |  |
| endAnimation():Void |  |
| getAirdashCount():Int |  |
| getAssistCharge():Float |  |
| getAssistContentStat(name:String):Dynamic |  |
| getAssistController():AssistController |  |
| getAssistName():String |  |
| getAssists():Array<Assist> |  |
| getCharacterStat(name:String):Dynamic |  |
| getDamageCounterAssistSprite():Sprite |  |
| getDamageCounterName():String | Gets the current display name on the damage counter |
| getDamageCounterRenderSpriteFront():Sprite | Returns the character sprite displayed on the front layer of the damage counter |
| getDefaultDamageCounterName():String | Gets the default damage counter display name |
| getDoubleJumpCount():Int |  |
| getFoes():Array<Character> |  |
| getHeldControls():ControlsObject | Returns the held controls for the character. This data may be modified by the input buffer or other input post-processing. |
| getLives():Int |  |
| getPlayerConfig():PlayerConfig |  |
| getPlayerTagContainer():Container | Get container of the player tag if it exists. |
| getPortColor():Int | Returns color of the player's port. Returns cpuColor if character is CPU. |
| getPressedControls():ControlsObject | Returns the pressed controls for the character. This data may be modified by the input buffer or other input post-processing. |
| getRawHeldControls():ControlsObject | Returns the raw held controls for the character. This data is not modified by the input buffer or any other input post-processing. |
| getScore():Score |  |
| getStockIconSprites():null | Returns the stock icon sprites.<br> The array `icons` corresponds to the sprites for te first four stocks<br> and `compactIcon` corresponds to the sprite displayed when at 5 or more stocks. |
| getType():Int |  |
| inActionableState():Bool | Returns true if the character is in a state that is free to act out of, like idle or fall. |
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
| setDamageCounterName(name:String):Void | Sets the  display name on the damage counter<br>Parameters:<br>- **name** - the new display name |
| setDoubleJumpCount(count:Int):Int |  |
| setLives(lives:Int):Void |  |
| updateAnimationStats(stats:Dynamic):Void |  |
| updateCharacterStats(stats:CharacterStatsProps):Void |  |


