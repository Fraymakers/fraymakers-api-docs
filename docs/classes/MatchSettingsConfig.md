---
layout: page
title: MatchSettingsConfig
---

A class containing parameters that configures the default settings of a Match.<br> Any player-affecting parameters will be overridden by the PlayerConfig.

## Static Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| NETCODE_DELAY | Int | `1` | netcodeType value: Delay-based netcode is enabled |
| NETCODE_NONE | Int | `0` | netcodeType value: No netcode is enabled |
| NETCODE_ROLLBACK | Int | `2` | netcodeType value: Rollback netcode is enabled |
| NETCODE_ROLLBACK_SIMULATED | Int | `3` | netcodeType value: Rollback netcode is simualted offline |


## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| damageDisplay | Bool | `true` | Set to true to display player damage on the HUD. Set to false to hide it. |
| damageMode | Bool | `true` | Damage mode for the players.<br> - true for damage<br> - false for stamina |
| damageRatio | Float | `1` | This value is applied to the global knockback formula when a game object takes damage. <br> - Do note that as the damage scales, so does the distance a foe goes upon being hit. |
| entrances | Bool | `true` | When true, character entrance animations will be shown at the start of a match. Set to false to disable this behavior. |
| hazards | Bool | `false` | Controls whether stage hazards are enabled. The definition of 'hazard' varies by stage.<br> - When set to true, stages' hazardous elements are enabled.  <br> - When set to false, they are disabled. |
| lives | Int | `-1` | Number of 'stocks' each player has by default within this Match. Note that this can be overridden by playerConfigs. <br> - Set to -1 to disable. |
| matchRules | Array<ResourceIdentifier> | `null` | The content/resource ID of the match rules for this match. |
| metadata | Dynamic | `null` | Dynamic metadata - use this for anything else not covered by existing variables. |
| music | ResourceIdentifier | `null` | This setting specifies the music resource id and content id to be loaded and played at match start |
| netcodeInputBuffer | Int | `null` | The input delay setting of the match host. For delay-based matches, all players will use the same input delay. For rollback-based matches, the settings are determined at an individual player level. |
| netcodeType | Int | `0` | Netcode setting. This determines the type of Match instance to instantiate. |
| pauseMenuId | String | `null` | The pause config for this match. |
| playerIDs | Bool | `false` | Set to true to make player ID numbers display above each player at all times. If player tags are available will display that instead. |
| randSeed | String | `null` | This is the random seed that was set at match start.  <br> You may retrieve this value if desired butthis should not be set manually. |
| sizeRatio | Float | `1` | A multiplier for the default scale of sprites within this Match.  <br> Generally this should be left alone, as it does not have additional effects like scaling physics or damage. |
| specialModes | Int | `0` | This is a bit mapping of the enabled special modes for a match.   <br> In order to combine special modes together, you need to perform a bitwise OR on the special modes you would like to enable. |
| stage | ResourceIdentifier | `null` | The content/resource ID of the Stage that the Match takes place on. |
| startDamage | Float | `0` | Starting damage for players. <br> - Set to negative to give players stamina instead of racking up damage.<br> @see stamina |
| teamAttack | Bool | `false` | Controls whether friendly fire is enabled.  <br> - When set to true, teammates can hurt each other.  <br> - This has no effect outside of team battles. |
| teams | Bool | `false` | Set to true to make the match a team battle. Set to false for a free-for-all.<br> - When having a team battle make sure to assign each player (via PlayerConfig) to a team. |
| time | Float | `0` | Match game timer IN SECONDS.  <br> - Set negative to count up from 0 to value.<br> - Set positive to count down from value.  <br> - Set to 0 to disable. |


