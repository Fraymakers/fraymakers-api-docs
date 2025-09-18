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
| getDamageCounterScore():Int | Get the score that is currently displayed on the damage counter.<br> Not necessarily the score used to determine the winner. |
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
| getTotalWallClings():Int | Returns the total number of wall clings the character has performed this airtime |
| getTotalWallJumps():Int | Returns the total number of wall jumps the character has performed this airtime |
| getType():Int |  |
| getVisible():Bool | Returns true if the character is visible, respects match modifiers |
| inActionableState():Bool | Returns true if the character is in a state that is free to act out of, like idle or fall. |
| inAerialAttackState():Bool |  |
| inAirdashCanceledAnimation():Bool |  |
| inBufferInputState():Bool | Helper for determining if the character is in a state that should cause inputs to be buffered. This includes some non-state related conditions like being in hitstop or shieldstun. |
| inHurtState():Bool |  |
| inSpecialAttackState():Bool |  |
| inStrongAttackChargeState():Bool |  |
| isBufferInputState(state:Int):Bool | Helper for checking if a state is valid state for inputs to be buffered. |
| isDisabledBySingleUse(state?:Int):Bool | Check if a state was used in the air while having the singleUse animation stat.<br> <br>Parameters:<br>- **state** - The state to check. If not specified, checks the current state |
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
| resetSingleUse(state?:Int):Void | Re-enable state(s) that were used in the air while having the singleUse animation stat.<br> <br>Parameters:<br>- **state** - The state to re-enable. If not specified, will re-enable all states |
| setAirdashCount(count:Int):Int |  |
| setAssistCharge(value:Float):Void |  |
| setAssistCutinAnimation(animation:String):Void |  |
| setDamageCounterName(name:String):Void | Sets the  display name on the damage counter<br>Parameters:<br>- **name** - the new display name |
| setDamageCounterScore(newScore:Int, options?:ScoreUpdateOptions):Void | Update the score that should be displayed on the damage counter.<br> Not necessarily the score used to determine the winner. |
| setDoubleJumpCount(count:Int):Int |  |
| setLives(lives:Int):Void |  |
| setTotalWallClings(count:Int):Int | Sets the total number of wall clings the character has performed this airtime |
| setTotalWallJumps(count:Int):Int | Sets the total number of wall jumps the character has performed this airtime |
| toStateFromInput(state:Int, animationOverride?:String):Void | Transitions the entity to a new state, taking into account the object's state transition map and animation rules. Note that the the target state is not guaranteed to be the current state after this function is called, so it's important to check the state after calling this function if you need to know the result.<br> Respects turbo mode cancel logic<br>Parameters:<br>- **state** - The state to transition to.<br>- **animationOverride** - Overrides the animation to use for the state transition. |
| updateAnimationStats(stats:Dynamic):Void |  |
| updateCharacterStats(stats:CharacterStatsProps):Void |  |


