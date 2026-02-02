---
layout: page
title: Shake
---

## Static Functions

| Function Name | Description |
| --------------- | ------------- |
| create():Shake | Creates a Shake instance |


## Instance Functions

| Function Name | Description |
| --------------- | ------------- |
| amplitude():Float | Returns the current value of the shake, based on the time passed since started. |
| cancel():Void | Stops the shake. |
| isShaking():Bool | Returns true if the shake is in progress |
| start(config:ShakeConfig):Void | Starts the shake using values from the passed config<br> <br> @see ShakeConfig |
| update():Void | Updates the Shake instance. Call this every frame. |


