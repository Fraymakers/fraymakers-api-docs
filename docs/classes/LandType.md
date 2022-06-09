---
layout: page
title: LandType
---

## Static Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| CUSTOM | Int | `n/a` | The engine will do nothing at all, except for allow the user to override with their own behaviour. |
| LINK_FRAMES | Int | `n/a` | The engine will perform landing-associated code, will change animations to the provided landAnimation but will preserve state. Additionally, the frame the entity was on will be skipped to.<br> As much as possible, this new animation is treated as though it were the original animation, so some stat values are ignored. |
| NONE | Int | `n/a` | The engine will not handle landing at all, and you'll instead just float above the ground. |
| NORMAL | Int | `n/a` | The engine will perform landing-associated code, and will attempt to send to the LAND state and change animations. Can be overridden. |
| TOUCH | Int | `n/a` | The engine will perform landing-associated code but otherwise will not do anything. |


