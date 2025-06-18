---
layout: page
title: Camera
---

## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| addEventListener(type:Int, func:Listener, options?:EventListenerOptions):Void |  |
| addForcedTarget(entity:Entity):Void |  |
| addTarget(entity:Entity):Void |  |
| addTimedTarget(entity:Entity, length:Int):Void |  |
| addTimedTargetPoint(point:Point, length:Int):Void |  |
| deleteForcedTarget(entity:Entity):Void |  |
| deleteTarget(entity:Entity):Void |  |
| deleteTimedTarget(entity:Entity):Void |  |
| deleteTimedTargetPoint(point:Point):Void |  |
| getBackgroundContainer():Container |  |
| getBackgroundContainers():Array<Container> |  |
| getForegroundContainer():Container |  |
| getMode():Int |  |
| getParallaxSprites():Array<Sprite> |  |
| getViewportHeight():Float |  |
| getViewportWidth():Float |  |
| getX():Float |  |
| getY():Float |  |
| getZoomScaleX():Float |  |
| getZoomScaleY():Float |  |
| hasEventListener(type:Int, func?:Listener):Bool |  |
| horizontalShake(intensity:Float, duration?:Int, frequency?:Float, waveType?:Int, decayType?:Int, customWaveSamples?:Array<Float>, customDecaySamples?:Array<Float>):Void |  |
| isDisposed():Bool |  |
| removeEventListener(type:Int, func:Listener):Void |  |
| setBackgroundOffset(index:Int, x:Float, y:Float):Void | Adjust a background container's view body offset. Useful for creating automatic scroll.<br>Parameters:<br>- **index** - Index of the background to offset<br>- **x** - X offset<br>- **y** - Y offset |
| setLockedPosition(x:Float, y:Float):Void | Set the camera to a locked position. This is only used when the camera is in locked mode.<br>Parameters:<br>- **x** - The x coordinate of the locked position<br>- **y** - The y coordinate of the locked position |
| setLockedZoom(zoomX:Float, zoomY:Float):Void | Set the camera to a specific zoom amount. Forces the camera into zoom mode if not already in zoom or locked modes.<br> 1x zoom is the default, and 0.5x zoom is zoomed out to show twice the area.<br>Parameters:<br>- **zoomX** - The x zoom factor to apply to the camera<br>- **zoomY** - The y zoom factor to apply to the camera |
| setMode(mode:Int):Int |  |
| shake(intensity:Float, duration?:Int, frequency?:Float, waveType?:Int, decayType?:Int, customWaveSamples?:Array<Float>, customDecaySamples?:Array<Float>):Void |  |
| verticalShake(intensity:Float, duration?:Int, frequency?:Float, waveType?:Int, decayType?:Int, customWaveSamples?:Array<Float>, customDecaySamples?:Array<Float>):Void |  |


