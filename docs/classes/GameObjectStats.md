---
layout: page
title: GameObjectStats
---

Stats for a tangible ingame object that appears in a match.

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| aerialFootPosition | Float | `0` | Foot collision point based on the relative vertical distance from the object's origin when the object is grounded. Note that positive numbers will have their signed flipped automatically since the foot position can never be beneath the object's origin point, so you may use positive numbers as a shorthand. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| aerialFriction | Float | `0.15` | The deceleration speed of the game object if forward is not held and they're in the air. |
| aerialHeadPosition | Float | `80` | Head collision point based on the relative vertical distance from the object's origin when the object is grounded. Note that positive numbers will have their signed flipped automatically since the head position can never be beneath the object's origin point, so you may use positive numbers as a shorthand. The head position will also be forced to be no lower than the foot. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| aerialHipWidth | Float | `25` | Width of wall collision detection area surrounding the object when the object is grounded. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| aerialHipXOffset | Float | `0` | Horizontally displaces the position of the hips from the base position of the object by the specified value when the object is grounded. At zero, the left and right hips are evenly displaced on both sides. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| aerialHipYOffset | Float | `0` | Vertically displaces the wall collision detection area on the object relative to the foot when the object is grounded. At zero, the hip is placed vertically halfway between the object's head and foot. This is the base value which is used when no collision body data is available. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| aerialSpeedAcceleration | Float | `0.45` | Game object's aerial drift acceleration (and deceleration if holding the opposite direction). |
| aerialSpeedCap | Float | `2.5` | Max horizontal speed when in the air. |
| attackRatio | Float | `1` | Multiplier that is applied to knockback which gets assigned to HitboxStats on attack hit.  This is similar to damageRatio but is instead applied to outgoing attacks from this object. This is especially useful for scaling up difficulty during single player matches. |
| baseScaleX | Float | `1` | Multiplies the base horizontal scale of the GameObject by the specified amount. The object will render by default at a multiple of baseScaleX and baseScaleY. Note that currently Special Angles AUTOLINK_STRONGER and AUTOLINK_STRONGEST will not function properly if this is set to a value other than 1.0. |
| baseScaleY | Float | `1` | Multiplies the base vertical scale of the GameObject by the specified amount. The object will render by default at a multiple of baseScaleX and baseScaleY. Note that currently Special Angles AUTOLINK_STRONGER and AUTOLINK_STRONGEST will not function properly if this is set to a value other than 1.0. |
| cameraBoxHeight | Float | `75` | Height of the camera box surrounding the object. The top left of the camera box will always be positioned so that it is mirrored over the Y-axis, with the bottom of the box flushed against the X axis. Use cameraBoxOffsetY to adjust the Y positioning from there. |
| cameraBoxOffsetX | Float | `25` | Offsets the X position of the camera box surrounding the object. |
| cameraBoxOffsetY | Float | `0` | Offsets the Y position of the camera box surrounding the object. |
| cameraBoxWidth | Float | `100` | Width of the camera box surrounding the object. The top left of the camera box will always be positioned so that it is mirrored over the Y-axis, with the bottom of the box flushed against the X axis. Use cameraBoxOffsetX to adjust the X positioning from there. |
| damageRatio | Float | `1` | Multiplier that is applied to received knockback.  This is similar to attackRatio but is instead applied to incoming attacks. This is especially useful for scaling up difficulty during single player matches. |
| deathBoundsDestroy | Bool | `true` | Whether or not to destroy the object when it touches a stage's death bounds |
| floorFootPosition | Float | `0` | Foot collision point based on the relative vertical distance from the object's origin when the object is grounded. Note that positive numbers will have their signed flipped automatically since the foot position can never be beneath the object's origin point, so you may use positive numbers as a shorthand. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| floorHeadPosition | Float | `80` | Head collision point based on the relative vertical distance from the object's origin when the object is grounded. Note that positive numbers will have their signed flipped automatically since the head position can never be beneath the object's origin point, so you may use positive numbers as a shorthand. The head position will also be forced to be no lower than the foot. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| floorHipWidth | Float | `25` | Width of wall collision detection area surrounding the object while grounded. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| floorHipXOffset | Float | `0` | Horizontally displaces the position of the hips from the base position of the object by the specified value when the object is grounded. At zero, the left and right hips are evenly displaced on both sides. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| floorHipYOffset | Float | `0` | Vertically displaces the wall collision detection area on the object relative to the foot when the object is grounded. At zero, the hip is placed vertically halfway between the object's head and foot. This is the base value which is used when no collision body data is available. Game Objects can override this value on specific animation frames by containing an ECB baked into the animation. |
| friction | Float | `0.66` | Deceleration rate on the ground. |
| ghost | Bool | `false` | Whether or not to enable structure collisions. |
| gravity | Float | `0` | Fall acceleration. |
| groundSpeedAcceleration | Float | `0` | Game object's ground speed acceleration. |
| groundSpeedCap | Float | `15` | Max horizontal speed when in the air. |
| immovable | Bool | `false` | Immovable objects are immune to windboxes and cannot be pushed by other solid entities. They will still push other solid objects if both the object and animation's solid stat is true. |
| initialState | Int | `-1` | The initial state the object should be set to. |
| metadata | Dynamic | `null` | Additional Metadata |
| shadows | Bool | `true` | Whether or not to enable shadows globally on the game object. |
| solid | Bool | `true` | Solid entities' animations push other solid objects away unless their immovable stat true, and can be pushed by other solid objects unless their own immovable stat is true. |
| spriteContent | String | `null` | Content id path of the sprite to load for this GameObject |
| stateTransitionMapOverrides | StateTransitionMap | `null` | Map of states to animations/callbacks |
| terminalVelocity | Float | `0` | The terminal velocity of the owner Entity. This is the maximum limit to the speed at which an Entity can fall. Please note however that knockback is not taken into account. |
| weight | Float | `100` | Used to determine how hard the ground shakes when the Entity lands or hits a wall, also used to determine how light the Entity is for knockback velocity purposes. |


