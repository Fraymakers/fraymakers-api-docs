---
layout: page
title: CharacterAnimationStats
---

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| allowFastFall | Bool | `false` | When true the character will accept fast fall inputs while in the air during the animation. |
| allowJump | Bool | `false` | When true the character will be able to jump cancel the animation. |
| allowMovement | Bool | `false` | When true, the player can influence the character's movement during this animation. |
| allowTurn | Bool | `false` | When true the character will be capable of flipping their direction faced on the first frame of the animation when the opposite direction is tapped prior to the animation. |
| allowTurnOnFirstFrame | Bool | `false` | When true the character will be capable of flipping their direction faced by tapping a left or right direction for the duration of the animation. |
| autocancel | Bool | `false` | When true, landing during this animation will ignore the value of landAnimation and send the character to the default landing animation. |
| doubleJumpCancel | Bool | `false` | Set to true to make upward momentum from a double jump cancel when this move is used. |
| grabLedgeBehind | Bool | `true` | If set to true the entity will be able to grab ledges from behind them if the type of object allows. |
| grabLedgeRising | Bool | `false` | If set to true the entity will be able to grab ledges while rising. |
| singleUse | Bool | `false` | Set to true for attack animations that can only be used once when initiated in mid-air. |


