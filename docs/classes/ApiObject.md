---
layout: page
title: ApiObject
---

Base class for any API-wrapped object

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| exports | Dynamic | `null` | Generic exports object accessible via the Api's global scope. Arbitrary variables and functions can be attached to it, but note that this object will not be automatically serialized for rollback. |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| isDisposed():Bool |  |
| makeArray(value:Array<Dynamic>):ApiVarArray | Allocates an Array of objects references. Note that this data type only serializes the pointer to the objects you set it to rather than literally serializing the data within the object. When the historical state of your ApiVarerenceArray is popped, the reference to the Array that existed at the time the history was last pushed will be restored.<br>Parameters:<br>- **value** - Object reference array to serialize |
| makeBool(value:Bool):ApiVarBool | Allocates a serializable boolean<br>Parameters:<br>- **value** - Initial value of boolean |
| makeEaseTimer(from:Float, to:Float, length:Int, easeType?:Int):EaseTimer | Allocates a rollback-friendly EaseTimer instance that will be automatically destroyed when this object is disposed of. |
| makeFloat(value:Float):ApiVarFloat | Allocates a serializable float<br>Parameters:<br>- **value** - Initial value of float |
| makeFrameTimer(initDuration:Int):FrameTimer | Allocates a rollback-friendly FrameTimer instance that will be automatically destroyed when this object is disposed of. |
| makeInt(value:Float):ApiVarInt | Allocates a serializable integer<br>Parameters:<br>- **value** - Initial value of integer |
| makeObject(value:Dynamic):ApiVarObject | Allocates a serializable object. Unlike serializable primitives, this only serializes the pointer to the objects you set it to rather than literally serializing the data within the object. When the historical state of your ApiObject is popped, the reference to the object that existed at the time the history was last pushed will be restored. ApiObjects will be serialized by the engine, however for anonymous structures you must manage their internal history yourself.<br>Parameters:<br>- **value** - Object to store a reference to |
| makePoint(x?:Float, y?:Float):Point | Allocates a rollback-friendly Point instance that will be automatically destroyed when this object is disposed of. |
| makeString(value:String):ApiVarString | Allocates a serializable string. Maximum limit of serializable strings is currently 4 per object.<br>Parameters:<br>- **value** - Initial value of string |


