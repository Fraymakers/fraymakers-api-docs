---
layout: page
title: Stage
---

## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| addEventListener(type:Int, func:Listener, options?:EventListenerOptions):Void |  |
| addTimer(interval:Int, repeats:Int, func, options?:IntervalTimerOptions):Int |  |
| getBackgroundBehindContainer():Container |  |
| getBackgroundEffectsContainer():Container |  |
| getBackgroundShadowsContainer():Container |  |
| getBackgroundStructuresContainer():Container |  |
| getCameraAnchors():Array<RectCollisionArea> |  |
| getCameraBounds():RectCollisionArea |  |
| getCharactersBackContainer():Container |  |
| getCharactersContainer():Container |  |
| getCharactersFrontContainer():Container |  |
| getCurrentFrame():Int |  |
| getDeathBounds():RectCollisionArea |  |
| getForegroundEffectsContainer():Container |  |
| getForegroundFrontContainer():Container |  |
| getForegroundShadowsContainer():Container |  |
| getForegroundStructuresContainer():Container |  |
| getMatchGraphicsContainer():Container | Get the container in which match graphics are rendered in.<br> This container is layered above the hud and all stage/camera layers. |
| getResource():Resource |  |
| getTotalFrames():Int |  |
| hasAnimation(animation:String):Bool |  |
| hasEventListener(type:Int, func?:Listener):Bool |  |
| isDisposed():Bool |  |
| pause():Void |  |
| playAnimation(name:String):Void |  |
| playFrame(frame:Int):Void |  |
| playLabel(label:String):Void |  |
| removeEventListener(type:Int, func:Listener):Void |  |
| removeTimer(uid:Int):Bool |  |
| resume():Void |  |
| updateLightboxStats(id:Int, lightboxStats:LightboxStatsProps):Void | Not currently implemented, will have no effect. |


