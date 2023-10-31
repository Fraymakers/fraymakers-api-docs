---
layout: page
title: VfxStats
---

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| animation | String | `null` | Name of the Vfx animation to play |
| chain | VfxStatsProps | `null` | Stats for a child Vfx to generate, inheriting all of the properties of its parent by default |
| fadeOut | Bool | `false` | When true, the Vfx animation will fade out linearly from initial spawn to timeout. |
| flipWith | Bool | `true` | Whether or not to flip the effect based on the calling GameObject's horizontal scale |
| forceVisible | Bool | `false` | When true, The Vfx will be shown regardless of any optimization settings/configs |
| layer | String | `null` | Specifies the layer to render the Vfx on which can be any valid VfxLayer constant. Defaults to VfxLayer.CHARACTERS_FRONT. |
| loop | Bool | `false` | When true, the Vfx animation will loop. |
| physics | Bool | `false` | When true, the Vfx will respond to physics-related methods |
| relativeWith | Bool | `true` | Whether or not to force relative positioning of the effect against the GameObject's position |
| resizeWith | Bool | `true` | Whether or not to scale the effect with the calling GameObject's current scale |
| rotation | Float | `0` | Rotation of the Vfx in degrees |
| scaleX | Float | `1` | Horizontal scale of the Vfx |
| scaleY | Float | `1` | Vertical scale of the Vfx |
| shrink | Bool | `false` | When true, the Vfx animation will scale down linearly from initial spawn to timeout. |
| smoothing | Bool | `false` | Whether or not to enable smoothing on the Vfx Sprite |
| spriteContent | String | `null` | Content path for sprite entity of the Vfx |
| timeout | Int | `-1` | How long to wait in frames before the Vfx should be removed. This also affects how long fade out and shrink should last (default: 0 = no timeout) |
| x | Float | `0` | Absolute x position of the Vfx |
| y | Float | `0` | Absolute y position of the Vfx |


