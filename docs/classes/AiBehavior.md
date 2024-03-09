---
layout: page
title: AiBehavior
---

## Static Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| ATTACK | Int | `0` | CPUs will fight taking their normal CPU level into account. This is the default behavior for a CPU unless otherwise specified. |
| EVADE | Int | `2` | CPUs will to avoid the player by running away, jumping, and rolling. |
| HUMAN | Int | `6` | CPUs will be controlled by human input. |
| IDLE | Int | `1` | CPUs will stand still while onstage, but will attempt to recover when knocked offstage. This is also the behavior for CPUs that are set to level 0. |
| JUMP | Int | `4` | CPUs  will constantly jump in place. |
| SHIELD | Int | `5` | CPUs will constantly shield in place. |
| WALK | Int | `3` | CPUs will walk forward constantly, turning around when approaching the edge of a stage or platform. |


