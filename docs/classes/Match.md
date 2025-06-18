---
layout: page
title: Match
---

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| firstBloodCalled | Bool | `false` |  |
| globals | Dynamic | `n/a` |  |
| overtimeCount | Int | `0` |  |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| addEventListener(type:Int, func:Listener, options?:EventListenerOptions):Void |  |
| addTimer(interval:Int, repeats:Int, func, options?:IntervalTimerOptions):Int |  |
| checkFirstBlood(foe:Character):Bool | Check if a valid first blood<br> <br> |
| checkTwoPlayersLastLife():Bool | Check if last 2 players and at their final stock |
| createCustomApiObject(customApiObjectContent:String, owner?:ApiObject):CustomApiObject |  |
| createCustomGameObject(customGameObjectContent:String, owner?:GameObject):GameObject |  |
| createLineSegmentStructure(points:Array<Float>, stats?:StructureStats):CustomLineSegmentStructure |  |
| createProjectile(projectileContent:String, owner?:GameObject):Projectile |  |
| createRibbonTrail(sprite:Sprite, segments:Int, singleAnchor:Bool):RibbonTrail |  |
| createShockwaveEffect(eventData:IShockwaveEffectEventData):Void |  |
| createSpriteStructure(sprite:Sprite):Structure |  |
| createStructure(structureContent:String):Structure |  |
| createVfx(vfxStats:VfxStats, owner?:GameObject):Vfx |  |
| freezeScreen(duration:Int, allowList:Array<GameObject>):Void | Freezes the screen, including all game objects<br>Parameters:<br>- **duration** - Length of the freeze<br>- **allowList** - Entities that will be allowed to update |
| getCamera():Camera |  |
| getCharacters():Array<Character> |  |
| getCollisionAreaByName(name:String):CollisionArea |  |
| getCollisionAreas():Array<CollisionArea> |  |
| getCustomGameObjects():Array<CustomGameObject> |  |
| getElapsedFrames():Int | Returns the amount of frames that have elapsed since the match started. |
| getMatchSettingsConfig():MatchSettingsConfig |  |
| getPlayers():Array<Character> |  |
| getProjectiles():Array<Projectile> |  |
| getStructureByName(name:String):Structure |  |
| getStructures():Array<Structure> |  |
| getTimeLeft():Int | Returns time (in frames) left in the match |
| hasEventListener(type:Int, func?:Listener):Bool |  |
| isDisposed():Bool |  |
| isReplay():Bool |  |
| removeEventListener(type:Int, func:Listener):Void |  |
| removeTimer(uid:Int):Bool |  |
| spawnKOBlast(owner:GameObject):Vfx |  |


