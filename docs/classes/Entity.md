---
layout: page
title: Entity
---

## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| addEventListener(type:Int, func:Listener, options?:EventListenerOptions):Void |  |
| addFilter(filter:Filter):Void |  |
| addShader(shader:Shader):Void |  |
| addTimer(interval:Int, repeats:Int, func, options?:IntervalTimerOptions):Int |  |
| attachToFloor(structure:Structure):Bool |  |
| bringInFront(gameObject:GameObject):Void |  |
| collisionTest(otherEntity:Entity, myBoxType:Int, theirBoxType:Int, bailEarly:Bool):Array<Rectangle> |  |
| collisionTestGroup(sourceEntities:Array<Entity>, sourceBoxType:Int, otherEntity:Entity, targetBoxType:Int, bailEarly:Bool):Array<EntityCollisionResult> | Takes in a group of entities, extracts their collision data, and then tests that collision data against another entity as if the collision data belonged to this<br> 		entity:EntityApi		The source entity whose collision data was responsible for the collision<br> 		result:Rectangle		A rectangle representing the overlapping space |
| faceLeft():Void |  |
| faceRight():Void |  |
| finalFramePlayed():Bool |  |
| flip():Void |  |
| flipX(value:Float):Float |  |
| getAlpha():Float |  |
| getAnimation():String |  |
| getBottomLayer():Container |  |
| getCollisionBoxes(boxType:Int):Array<CollisionBox> |  |
| getCurrentFloor():Structure |  |
| getCurrentFrame():Int |  |
| getEcbCollisionBox():CollisionBox |  |
| getEcbFootX():Float |  |
| getEcbFootY():Float |  |
| getEcbHeadX():Float |  |
| getEcbHeadY():Float |  |
| getEcbLeftHipX():Float |  |
| getEcbLeftHipY():Float |  |
| getEcbRightHipX():Float |  |
| getEcbRightHipY():Float |  |
| getKnockback():Float |  |
| getNetSpeed():Float |  |
| getNetXVelocity():Float |  |
| getNetYVelocity():Float |  |
| getPivotX():Float | Returns the unscaled x-position of the entity's pivot point |
| getPivotXScaled():Float | Returns the scaled x-position of the entity's pivot point |
| getPivotY():Float | Returns the unscaled y-position of the entity's pivot point |
| getPivotYScaled():Float | Returns the scaled y-position of the entity's pivot point |
| getPreviousState():Int |  |
| getPreviousStateGroup():Int |  |
| getResource():Resource |  |
| getRotation():Float |  |
| getScaleX():Float |  |
| getScaleY():Float |  |
| getState():Int |  |
| getStaticBottomLayer():Container |  |
| getStaticTopLayer():Container |  |
| getTopLayer():Container |  |
| getTotalFrames():Int |  |
| getType():Int |  |
| getUid():Int |  |
| getViewRootContainer():Container |  |
| getVisible():Bool |  |
| getX():Float |  |
| getXKnockback():Float |  |
| getXSpeed():Float |  |
| getXVelocity():Float |  |
| getY():Float |  |
| getYKnockback():Float |  |
| getYSpeed():Float |  |
| getYVelocity():Float |  |
| hasAnimation(animation:String):Bool |  |
| hasEventListener(type:Int, func?:Listener):Bool |  |
| hitTestEntity(otherEntity:Entity, selfCollisionBoxType:Int, otherCollisionBoxType:Int, options?:HitTestEntityOptions):Array<CollisionResult> |  |
| hitTestStructuresWithLineSegment(point1:Point, point2:Point, intersectionOut?:Point, options:StructureColliderSearchOptions):Array<Structure> |  |
| inState(state:Int):Bool |  |
| inStateGroup(stateGroup:Int):Bool |  |
| isDisposed():Bool |  |
| isFacingLeft():Bool |  |
| isFacingRight():Bool |  |
| isOnFloor():Bool |  |
| kill():Void |  |
| move(x:Float, y:Float):Void |  |
| moveAbsolute(x:Float, y:Float):Void |  |
| pause():Void |  |
| playAnimation(name:String):Void |  |
| playFrame(frame:Int):Void |  |
| playFrameLabel(label:String):Void |  |
| refreshEcb():Void |  |
| removeEventListener(type:Int, func:Listener):Void |  |
| removeFilter(filter:Filter):Void |  |
| removeShader(shader:Shader):Void |  |
| removeTimer(uid:Int):Bool |  |
| resetMomentum():Void |  |
| resetRotation():Void |  |
| resume():Void |  |
| sendBehind(gameObject:GameObject):Void |  |
| setAlpha(value:Float):Float |  |
| setKnockback(speed:Float, angle:Float):Float |  |
| setRotation(value:Float):Float |  |
| setScaleX(scaleX:Float):Float | Sets the horizontal scale of the entity.<br> |
| setScaleY(scaleY:Float):Float | Sets the vertical scale of the entity.<br> |
| setState(state:Int):Void |  |
| setVisible(value:Bool):Bool |  |
| setX(pos:Float):Float |  |
| setXKnockback(speed:Float):Float |  |
| setXSpeed(speed:Float):Float |  |
| setXVelocity(speed:Float):Float |  |
| setY(pos:Float):Float |  |
| setYKnockback(speed:Float):Float |  |
| setYSpeed(speed:Float):Float |  |
| setYVelocity(speed:Float):Float |  |
| swapDepths(gameObject:GameObject):Void |  |
| toState(state:Int, animationOverride?:String):Void |  |
| toggleGravity(status:Bool):Void |  |
| unattachFromFloor():Void |  |


