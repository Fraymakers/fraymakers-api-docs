---
layout: page
title: Engine
---

## Static Functions

| Function Name | Description |
| --------------- | ------------- |
| forCount(count:Int, callback:Dynamic, args:Array<Dynamic>):Void | Utility method for running a for loop with a given duration that leverages the engine for more efficiency. Use this for demanding for loops with large lists to improve performance.<br>Parameters:<br>- **count** - Number of times the for loop should run.<br>- **callback** - A callback method to run that will receive the current zero-indexed loop number as its first argument. If this callback returns false, the loop will be ceased immediately.<br>- **args** - Any additional arguments to pass to the callback method (Set to empty array [] if you desire no additional arguments) |
| forEach(list:Array<Dynamic>, callback:Dynamic, args:Array<Dynamic>):Void | Utility method for running a for...in loop against a list that leverages the engine for more efficiency. Use this for demanding for loops with large lists to improve performance.<br>Parameters:<br>- **list** - The array containing the elements to loop through.<br>- **callback** - A callback method to run that will receive the current iteratee as its first argument, and index integer as its second argument. If this callback returns false, the loop will be ceased immediately.<br>- **args** - Any additional arguments to pass to the callback method (Set to empty array [] if you desire no additional arguments) |
| framesToTimeString(numFrames:Int):String | Returns formatted timestamp given # of frames. Includes milliseconds.<br> |
| framesToTimeStringShort(numFrames:Int):String | Returns formatted timestamp given # of frames. Does not include milliseconds.<br> |
| log(msg:Dynamic, color?:Int):Void |  |
| makeUid():Int |  |


