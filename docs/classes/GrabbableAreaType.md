---
layout: page
title: GrabbableAreaType
---

Governs which collision box type is used for grab collision

## Static Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| AUTO | Int | `n/a` | The engine will use the value in character stats. If used in character stats, will fall back to HURT |
| GRABBABLE | Int | `n/a` | The engine will use the grab->grabbablebox collision to determine grabs |
| HURT | Int | `n/a` | The engine will use the grab->hurtbox collision to determine grabs |
| NONE | Int | `n/a` | The engine will not allow grabs |


