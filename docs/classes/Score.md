---
layout: page
title: Score
---

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| damageGivenThisLife | Array<Float> | `n/a` | Total damage given to other characters, this life, split up by port. |
| damageGivenTotal | Array<Float> | `n/a` | Total damage given to other characters, split up by port. |
| damageTakenThisLife | Array<Float> | `n/a` | Total damage taken by other characters, this life, split up by port. |
| damageTakenTotal | Array<Float> | `n/a` | Total damage taken by other characters, split up by port. |
| falls | Int | `n/a` | Total Falls |
| framesSinceDamageTaken | Int | `n/a` | Frames since this player last took damage |
| kos | Int | `n/a` | Total ko's |
| kosThisLife | Int | `n/a` | Current ko's since death |
| multiKills | Array<Int> | `n/a` | Keeps track of list of ports that were ko'd and count toward multi-kill status |
| selfDestructs | Int | `n/a` | Total Self Destructs |
| shieldCombo | Int | `n/a` | Keeps track of successful shields since last damage given / received |
| timeDefeated | Int | `n/a` | Time elapsed when you were defeated |


