---
layout: page
title: Sprite
---

## Static Functions

| Function Name | Description |
| --------------- | ------------- |
| create(spriteContent:String):Sprite | Generates a Sprite object from a given content id path.<br>Parameters:<br>- **spriteContent** - The content id path of the sprite to be created. |
| createBatch(count:Int, spriteContent:String, animationId?:String, x?:Float, y?:Float, container?:Container):Array<Sprite> | Batch method for generating numerous amounts of sprites in one call.<br>Parameters:<br>- **count** - The number of sprites to create<br>- **spriteContent** - The content id path of the Sprite to create<br>- **animationId** - The animation for the sprite to display<br>- **x** - X location of the Sprite<br>- **y** - Y location of the Spirte<br>- **container** - The container the Sprite should be added to |


## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| currentAnimation | String | `n/a` |  |
| currentFrame | Int | `n/a` |  |
| totalFrames | Int | `n/a` |  |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| advance():Void |  |
| dispose():Void |  |
| getPalette():Map<Int,Int> |  |
| goToFrameLabel(label:String):Void |  |
| hasAnimation(animation:String):Bool |  |
| setPalette(value:Map<Int,Int>):Map<Int,Int> |  |


