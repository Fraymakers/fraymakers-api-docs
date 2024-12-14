---
layout: page
title: BodyStatus
---

## Static Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| ALL | Int | `n/a` | All body statuses will be applied. |
| DAMAGE_ARMOR | Int | `n/a` | Prevents damage and flinching up to the amount of damage specified by the bodyStatusStrength AnimationStats field. Attacking foes will still receive selfHitstop, and if the threshold is exceeded the full damage amount will be taken. |
| DAMAGE_RESISTANCE | Int | `n/a` | Prevents damage and flinching up to the amount of damage specified by the bodyStatusStrength AnimationStats field. Attacking foes will still receive selfHitstop, and if the threshold is exceeded the amount of damage received will be reduced by the amount specified by bodyStatusStrength. |
| INTANGIBLE | Int | `n/a` | Prevents interaction against foe hitboxes altogether. |
| INVINCIBLE | Int | `n/a` | Prevents taking damage, flinching, and being grabbed. Foes will still receive selfHitstop. |
| INVINCIBLE_GRABBABLE | Int | `n/a` | Prevents taking damage and flinching. Object remains grabbable and foes will still receive selfHitstop. |
| LAUNCH_ARMOR | Int | `n/a` | Prevents damage and flinching up to the amount of knockback velocity specified by the bodyStatusStrength AnimationStats field. Attacking foes will still receive selfHitstop, and if the threshold is exceeded the full knockback velocity amount will be applied. |
| LAUNCH_RESISTANCE | Int | `n/a` | Prevents damage and flinching up to the amount of knockback velocity specified by the bodyStatusStrength AnimationStats field. Attacking foes will still receive selfHitstop, and if the threshold is exceeded the amount of knockback velocity received will be reduced by the amount specified by bodyStatusStrength. |
| NONE | Int | `n/a` | No effect. |
| SUPER_ARMOR | Int | `n/a` | Prevents flinching. Damage will still be received, and attacking foes will still receive selfHitstop. |


