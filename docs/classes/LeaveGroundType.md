---
layout: page
title: LeaveGroundType
---

## Static Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| LINK_FRAMES | Int | `n/a` | The engine will attempt to change animations to the provided leaveGroundAnimation and will preserve the current state. Additionally, the frame the Character was on will be skipped to.<br> As much as possible, this new animation is treated as though it were the original animation, so some stat values are ignored. |
| NONE | Int | `n/a` | The engine will not do anything, the Character will remain in its current animation. |
| TO_FALL | Int | `n/a` | The engine will cancel the animation and send the Character to the FALL state.<br> If a leaveGroundAnimation is provided, the engine will play that animation instead of the default FALL state animation. |
| TRANSITION | Int | `n/a` | The engine will attempt to change animations to the provided leaveGroundAnimation, but will preserve the current state.<br> If no leaveGroundAnimation is provided or it is invalid, then the animation will not be canceled. |


