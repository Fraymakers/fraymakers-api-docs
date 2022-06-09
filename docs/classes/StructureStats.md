---
layout: page
title: StructureStats
---

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| animationId | String | `null` | The id of the animation to use for this structure |
| disableShadows | Bool | `false` | When true, shadows should be disabled from rendering on this structure. This is not implemented by the game engine, so you are expected to use it to your needs. |
| disabled | Bool | `false` | When true, this CollisionArea instance should become inactive and all hitTests should return false. |
| dropThrough | Bool | `false` | When false, the player should be disallowed from falling through the structure via any means. Set to true to permit structure drop-through capability for objects that utilize it. |
| foregroundAnimationId | String | `null` | The id of the foreground sprite to use for this structure |
| foregroundSpriteContent | String | `null` | Content id path of the foreground sprite to load for this structure |
| land | Bool | `true` | When true, objects can land on the structure. When false, the structure will still prevent objects from passing through however their structureCollision component will never register an object as "landed". (StructureType.FLOOR only). |
| leftLedge | Bool | `true` | When enabled, left ledge grabs will be enabled on this structure (StructureType.FLOOR only). |
| leftLedgeSize | Float | `null` | Determines the length of this structure's left ledges (StructureType.FLOOR only). |
| ricochet | Bool | `true` | When false, it will not be possible for game objects to bounce off this object |
| rightLedge | Bool | `true` | When enabled, right ledge grabs will be enabled on this structure (StructureType.FLOOR only). |
| rightLedgeSize | Float | `null` | Determines the length of this structure's right ledges (StructureType.FLOOR only). |
| spriteContent | String | `null` | The content id path of the sprite to load for this structure |
| startX | Float | `0` | Starting X position of the structure |
| startY | Float | `0` | Starting Y position of the structure |
| structureType | Int | `null` | The type of collision behavior to use on this structure |


