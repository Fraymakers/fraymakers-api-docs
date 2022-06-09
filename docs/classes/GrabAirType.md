---
layout: page
title: GrabAirType
---

Governs behaviour of the entity when GRAB is pressed midair

## Static Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| AERIAL | Int | `n/a` | The engine will perform an aerial attack, also taking into account the input direction |
| GRAB | Int | `n/a` | The engine will jump to the grab_air animation, if it exists. If no animation is found, acts like NONE |
| NONE | Int | `n/a` | The engine will do nothing, and essentially ignore the input |


