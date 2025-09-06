---
layout: page
title: GameObject
---

## Static Functions

| Function Name | Description |
| --------------- | ------------- |
| angleIsInSpikeThreshold(angle:Float):Bool | Returns true if the angle is within the spike threshold.<br> |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| addDamage(dmg:Float):Float |  |
| addStatusEffect(type:Int, value?:Float, options?:StatusEffectObjectOptions):StatusEffectObject |  |
| applyGlobalBodyStatus(status:Int, duration:Int):BodyStatusTimer |  |
| attemptGrab(foe:GameObject, options?:ForceGrabOptions):Bool | Attempt to grab the foe. <br> <br>Parameters:<br>- **options** - Instructions for the types of grab-safety checks to ignore |
| attemptHit(target:GameObject, hitboxStats:HitboxStats, collisionResult?:CollisionResult):Bool | Initiates processing as though a hitbox=>hurtbox collision was detected. Due to validation checks during processing, a "hit" may not occur.<br>Parameters:<br>- **target** - GameObject receiving the hit<br>- **hitboxStats** - Stats that determine the effect of the "hit"<br>- **collisionResult** - Optional object containing "boxes" that represent the positional information of any involved hitboxes during the hit. Can be useful for generating spatially aware hit effects, and will automatically adjust built-in hit effect positioning to the specified overlap box. |
| findStatusEffectObjectsByTag(type:Int, tag:String):Array<StatusEffectObject> |  |
| forceStartHitstop(value:Int, shake:Bool):Void | Forcibly starts a new set of hitstop. <br> @see GameObjectEvent.HITSTOP_END<br> @see GameObjectEvent.HITSTOP_START<br>Parameters:<br>- **value** - Duration in frames<br>- **shake** - True if camera should shake |
| forceStartHitstun(value:Int):Void | Forcibly starts a new set of hitstun. <br> @see GameObjectEvent.ENTER_HITSTUN<br> @see GameObjectEvent.EXIT_HITSTUN<br>Parameters:<br>- **value** - Duration in frames |
| getAllGrabbedFoes():Array<GameObject> | Returns all foes the grabbed foes array. |
| getAlpha():Float |  |
| getAnimationStat(name:String):Dynamic |  |
| getAnimationStatsMetadata():Dynamic |  |
| getCostumeIndex():Int |  |
| getCostumeShader():PaletteSwapShader |  |
| getDamage():Float |  |
| getDamageCounterContainer():Container |  |
| getDamageCounterRenderSprite():Sprite |  |
| getGameObjectStat(name:String):Dynamic |  |
| getGameObjectStatsMetadata():Dynamic |  |
| getGrabbedFoe():GameObject | Returns the first grabbed foe in the grabbed foes array. |
| getHitstop():Int |  |
| getHitstun():Int |  |
| getOffscreenIndicator():OffscreenIndicator |  |
| getOwner():GameObject |  |
| getPlayerBorder():PlayerBorder |  |
| getRootOwner():GameObject |  |
| getScaleX():Float |  |
| getScaleY():Float |  |
| getSizeMultiplier():Float |  |
| getSprite():Sprite |  |
| getStatusEffectByType(type:Int):StatusEffect |  |
| getTeam():Int |  |
| getVisible():Bool |  |
| hasBodyStatus(flags:Int):Bool |  |
| moveScaled(x:Float, y:Float):Void |  |
| pause():Void |  |
| reactivateHitboxes():Void | Refreshes the attack's UID allowing it to hit again. |
| releaseAllCharacters(grabReleaseKb?:Bool):Void |  |
| releaseCharacter(character:Character, grabReleaseKb?:Bool):Void |  |
| removeStatusEffect(type:Int, id:String):Bool |  |
| resume():Void |  |
| setAlpha(value:Float):Float |  |
| setCostumeIndex(costumeIndex:Int):Void |  |
| setCostumeShader(paletteSwapShader:PaletteSwapShader):Void |  |
| setDamage(dmg:Float):Float |  |
| setOwner(owner:GameObject):Void |  |
| setPlayerBorder(playerBorder:PlayerBorder):Void |  |
| setScaleX(scaleX:Float):Float |  |
| setScaleY(scaleY:Float):Float |  |
| setVisible(value:Bool):Bool |  |
| setXSpeedScaled(speed:Float):Float |  |
| setXVelocityScaled(velocity:Float):Float |  |
| setYSpeedScaled(speed:Float):Float |  |
| setYVelocityScaled(velocity:Float):Float |  |
| startHitstop(value:Int, shake:Bool):Bool | Attempts to start a new set of hitstop. Only starts a new set of hitstop if the new value is greater than the existing value. <br> @see GameObjectEvent.HITSTOP_END<br> @see GameObjectEvent.HITSTOP_START<br>Parameters:<br>- **value** - Duration in frames<br>- **shake** - True if camera should shake |
| startHitstun(value:Int):Bool | Attempts to start a new set of hitstun. Only starts a new set of hitstun if the new value is greater than the existing value. <br> @see GameObjectEvent.ENTER_HITSTUN<br> @see GameObjectEvent.EXIT_HITSTUN<br>Parameters:<br>- **value** - Duration in frames |
| takeHit(hitboxStats:HitboxStats, collisionResult?:CollisionResult):Bool |  |
| updateAnimationStats(stats:AnimationStatsProps):Void |  |
| updateAnimationStatsMetadata(stats:Dynamic):Void |  |
| updateGameObjectStats(stats:GameObjectStatsProps):Void |  |
| updateGameObjectStatsMetadata(stats:Dynamic):Void |  |
| updateHitboxStats(id:Int, stats:HitboxStatsProps):Void |  |
| validateHit(hitboxStats:HitboxStats):Bool |  |


