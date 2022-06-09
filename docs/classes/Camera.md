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
| setMode(mode:Int):Int |  |
| shake(intensity:Float, duration?:Int, frequency?:Float, waveType?:Int, decayType?:Int, customWaveSamples?:Array<Float>, customDecaySamples?:Array<Float>):Void |  |
| verticalShake(intensity:Float, duration?:Int, frequency?:Float, waveType?:Int, decayType?:Int, customWaveSamples?:Array<Float>, customDecaySamples?:Array<Float>):Void |  |


