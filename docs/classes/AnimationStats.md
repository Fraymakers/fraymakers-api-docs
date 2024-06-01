---
layout: page
title: AnimationStats
---

AnimationStats is the base class for animation behavior of GameObjects.

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| aerialSpeedAcceleration | Float | `-1` | Air speed acceleration override for this animation. Resorts to default aerialSpeedAcceleration GameObject stat when set to a negative value. |
| aerialSpeedCap | Float | `-1` | Maximum air speed limit override for this animation. Resorts to default aerialSpeedCap GameObject stat when set to a negative value. |
| attackId | Int | `0` | Not to be set directly - unique attackId for the attack |
| autoRotate | Bool | `false` | If true, the entity's body rotates to match momentum. |
| bodyStatus | BodyStatus | `BodyStatus.NONE` | Override's the BodyStatus of the Entity for the duration of the animation. |
| bodyStatusStrength | Float | `0` | If BodyStatus is in the DAMAGE_ARMOR, DAMAGE_RESISTANCE, LAUNCH_ARMOR, or LAUNCH_RESISTANCE states, then this controls the damage and velocity thresholds for each respective status. |
| chargeFramesMax | Int | `0` | Maximum number of frames the animation can be charged for. Setting this value to zero will disable charge incrementing |
| chargeFramesTotal | Int | `0` | Total number of frames the animation has been charged for |
| endType | AnimationEndType | `AnimationEndType.AUTO` | Defines how the engine should handle the completion of this animation<br> @see AnimationEndType |
| grabLimit | Int | `1` | Limit of the amount of objects that can be grabbed during this animation |
| gravityMultiplier | Float | `1` | Multiplier that is applied to the object's gravity value |
| groundSpeedAcceleration | Float | `-1` | Ground speed acceleration override for this animation. Resorts to default groundSpeedAcceleration GameObject stat when set to a negative value. |
| groundSpeedCap | Float | `-1` | Maximum ground speed limit override for this animation. Resorts to default groundSpeedCap GameObject stat when set to a negative value. |
| immovable | Bool | `false` | Immovable animations do not take knockback from windboxes and cannot be pushed by other solid objects, but may still push other movable solid objects. |
| interruptible | Bool | `false` | Allows the animation to be counted as a free state. Note that modifying this value directly will bypass any special rules surrounding interruptibility (i.e. IASA that relies on external conditions). |
| landAnimation | String | `null` | If non-null, the name of the animation that will be jumped to when the object transitions from air to ground, regardless of landType<br> If null, the engine will use a land animation based on the landType |
| landType | LandType | `LandType.NORMAL` | Determines the behavior of the object when it transitions from air to ground.<br> @see: LandType |
| leaveGroundCancel | Bool | `true` | If enabled the entity will have their animation canceled if they transition from grounded to aerial.<br> @deprecated Characters can use leaveGroundType instead |
| metadata | Dynamic | `null` | Metadata passed into the attack |
| name | String | `null` | The name of the attack animation. |
| nextAnimation | String | `null` | Used in conjunction with AnimationEndType.AUTO.  If provided, when the animation ends, the entity's animation will be changed to this value |
| nextState | Int | `-1` | Used in conjunction with AnimationEndType.AUTO. If provided, when the animation ends, the entity's state will be changed to this value |
| pause | Bool | `false` | When set to true, animation playback is halted on the current frame. |
| resetId | Bool | `true` | When true, the current AnimationStats attackId will be reset on the first frame. |
| resetRotation | Bool | `n/a` | When true, the rotation of the object will be reset on the first frame. |
| rotationSpeed | Float | `n/a` | When a non-zero value, the object will rotate at the specified speed. Positive values will rotate clockwise, while negative values will rotate counter-clockwise. Note that if the object is flipped horizontally, the direction of the rotation will also be flipped. |
| shadows | Bool | `true` | Whether or not to enable shadows on this particular animation |
| slideOff | Bool | `false` | Whether or not the character can slide off the edge of a floor. |
| solid | Bool | `true` | Set to true and the object will push other solid animations when hurtboxes overlap, unless those objects are immovable or non-solid. |
| storedChargePercent | Float | `0` | Not to be set directly - tracks the previously stored charge percentage |
| terminalVelocity | Float | `-1` | Terminal velocity override for this animation. Resorts to default terminalVelocity GameObject stat when set to a negative value. |
| xSpeedConservation | Float | `1` | Percentage of non-KB X Speed kept on frame 1 |
| ySpeedConservation | Float | `1` | Percentage of non-KB Y Speed kept on frame 1 |


