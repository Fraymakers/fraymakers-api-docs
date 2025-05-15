---
layout: page
title: PlayerConfig
---

A class containing parameters that configures the default settings of a Character in a match.<br> These override values given in the MatchConfig.

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| assist | ResourceIdentifier | `null` | The content/resource ID of the assist to load for the player. If set to null, this assist slot will be considered empty. |
| assistBorder | PlayerBorder | `null` | Specify a border to show on this assist |
| assistCostume | Int | `-1` | Assigns a costume to the assist. If this value set to a negative number, the default costume will be used. Otherwise this value corresponds to the index of the costume within the assist's costume array. |
| hasRandomAssist | Bool | `false` | Returns true if the assist was randomly selected. |
| startAssistCharge | Float | `-1` | Starting assist charge for players. This overrides the startAssistCharge value provided by the level data settings for the match unless set to -1. |
| unlimitedAssist | Bool | `false` | Unlimited final strongs? |


