---
layout: page
title: CharacterStats
---

## Instance Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| airdashAccelMultiplier | Float | `0.3` | The percentage of airdash momentum that is added each frame during accel phase |
| airdashCameraShakeIntensity | Int | `0` | How much camera shake the engine should apply at the beginning on your airdash |
| airdashCancelSpeedConservation | Float | `0.6` | The percentage of the airdash speed that will be conserved when canceling an airdash with an attack |
| airdashEffectOffsetX | Float | `0` | X offset of the air dash effect center point relative to the horizontal center of the character's body |
| airdashEffectOffsetY | Float | `0` | Y offset of the air dash effect center point relative to the vertical center of the character's body |
| airdashEffectRadius | Float | `10` | Radial distance away from the center point of the character that the air dash effect is drawn |
| airdashEndlagLength | Int | `6` | Number of frames at airdashEndlagSpeed |
| airdashEndlagSpeed | Float | `2` | Airdash endlag speed |
| airdashFullspeedLength | Int | `2` | Number of frames at airdashSpeedCap before deceleration starts |
| airdashInitialSpeed | Float | `10` | Airdash initial speed |
| airdashLimit | Int | `1` | Maximum number of times the character can air dash before landing (Set to 0 to disable, or negative for infinite) |
| airdashSpeedCap | Float | `12.5` | Airdash max speed |
| airdashStartupLength | Int | `3` | Number of frames at airdashInitialSpeed (note, gravity is enabled) before acceleration |
| airdashTrailEffect | String | `null` | The ID of the trail effect that you want airdashes to spawn |
| attackVoiceIds | Array<String> | `null` | List of attack voice content ids. Calls to playAttackVoice() will choose one of these audio clips at random. |
| attackVoiceSilenceRate | Float | `0.5` | The rate at which calls to playAttackVoice() should result in silence. |
| buryAnimation | String | `"hurt_thrown"` | The animation the character will use when buried. |
| buryFrame | Int | `13` | The frame of the buryAnimation to be used while buried. |
| buryOffsetY | Float | `0.0` | Vertical offset for the bury animation, relative to their ECB's vertical midpoint. |
| crawlSpeed | Float | `0` | Character's crawl speed. Set to 0 to disable crawling. |
| dashSpeed | Float | `1` | Character's initial run speed. |
| dodgeRollSpeed | Float | `10` | Speed the character's dodge roll begins at. |
| dodgeRollSpeedLength | Int | `1` | How many frames of speed are applied during dodge roll. |
| dodgeRollSpeedStartFrame | Int | `3` | Frame that dodge roll speed begins to be applied on. |
| doubleJumpSpeeds | Array<Float> | `null` | An array of the character's double jump speeds. Values less than or equal to zero will have no effect. The number of entries in the array correlates with how many double jumps the character will get from the engine. |
| fastFallSpeed | Float | `15` | The speed at which a character falls during a fast fall |
| floatDuration | Int | `0` | How long the character can float. 0 to disable. |
| getupRollSpeed | Float | `10` | Speed the character's getup roll begins at. |
| getupRollSpeedLength | Int | `1` | How many frames of speed are applied during getup roll. |
| getupRollSpeedStartFrame | Int | `2` | Frame that getup roll speed begins to be applied on. |
| grabAirType | Int | `null` | The behaviour of performing GRAB while midair |
| holdToJump | Bool | `false` | If set to true, jumps after the second can be performed by holding jump. |
| hurtHeavySilenceRate | Float | `0.5` | The rate at which calls to playHurtHeavyVoice() should result in silence. |
| hurtHeavyVoiceIds | Array<String> | `null` | List of hurt heavy voice content ids. Calls to playHurtHeavyVoice() will choose one of these audio clips at random. |
| hurtLightSilenceRate | Float | `0.5` | The rate at which calls to playHurtLightVoice() should result in silence. |
| hurtLightVoiceIds | Array<String> | `null` | List of hurt light voice content ids. Calls to playHurtLightVoice() will choose one of these audio clips at random. |
| hurtMediumSilenceRate | Float | `0.5` | The rate at which calls to playHurtMediumVoice() should result in silence. |
| hurtMediumVoiceIds | Array<String> | `null` | List of hurt medium voice content ids. Calls to playHurtMediumVoice() will choose one of these audio clips at random. |
| initialGlideSpeed | Float | `0` | Speed the character starts gliding at. 0 to disable. |
| jumpSpeed | Float | `10` | Character's grounded vertical jump speed. Values less than or equal to zero will disable the character's ability to jump from the ground |
| jumpSpeedBackwardInitialXSpeed | Float | `0` | Horizontal speed initially given if holding backward when jump startup ends. Set to greater than or equal to 0 to disable. |
| jumpSpeedForwardInitialXSpeed | Float | `0` | Horizontal speed initially given if holding forward when jump startup ends. Set to less than or equal to 0 to disable. |
| koVoiceIds | Array<String> | `null` | List of KO blast voice content ids. Calls to playKoVoice() will choose one of these audio clips at random. |
| koVoiceSilenceRate | Float | `0.5` | The rate at which calls to playKoVoice() should result in silence. |
| ledgeActionOccupancyTime | Int | `30` | How long a character occupies a ledge when performing ledge actions. |
| ledgeJumpXSpeed | Float | `2.5` | Horizontal speed boost the character gets when performing a ledge jump |
| ledgeJumpYSpeed | Float | `-10` | Vertical speed boost the character gets when performing a ledge jump |
| ledgeRollSpeed | Float | `10` | Speed the character's ledge roll begins at. |
| ledgeRollSpeedLength | Int | `1` | How many frames of speed are applied during ledge roll. |
| ledgeRollSpeedStartFrame | Float | `1` | Frame that ledge roll speed begins to be applied on. |
| name | String | `null` | The unique name of the character. Used for finding the object. |
| runSpeedAcceleration | Float | `1` | Character's run speed acceleration. |
| runSpeedCap | Float | `1` | Character's max run speed. |
| runSpeedInitial | Float | `1` | Character's initial run speed (post-turn only). |
| shieldBackHeight | Float | `90` | Height of the back shield graphic |
| shieldBackNineSliceContent | String | `"global::vfx.vfx_shield_back"` | Nine slice to use for the back shield |
| shieldBackWidth | Float | `40` | Width of the back shield graphic |
| shieldBackXOffset | Float | `0` | Horizontal offset of the character's back shield relative to the center of their body dimensions |
| shieldBackYOffset | Float | `0` | Vertical offset of the character's back shield relative to the center of their body dimensions |
| shieldCrossupThreshold | Float | `0` | Minimum distance behind character that attacker must be to get a cross-up |
| shieldFrontHeight | Float | `90` | Height of the front shield graphic |
| shieldFrontNineSliceContent | String | `"global::vfx.vfx_shield_front"` | Nine slice to use for the front shield |
| shieldFrontWidth | Float | `40` | Width of the front shield graphic |
| shieldFrontXOffset | Float | `0` | Horizontal offset of the character's front shield relative to the center of their body dimensions |
| shieldFrontYOffset | Float | `0` | Vertical offset of the character's front shield relative to the center of their body dimensions |
| shortHopSpeed | Float | `4` | The speed of a short-hop. |
| techRollSpeed | Float | `10` | Speed the character's tech roll begins at. |
| techRollSpeedLength | Int | `1` | How many frames of speed are applied during tech roll. |
| techRollSpeedStartFrame | Int | `7` | Frame that tech roll speed begins to be applied on. |
| walkSpeedAcceleration | Float | `1` | Character's walk speed acceleration. |
| walkSpeedCap | Float | `1` | Character's max walk speed. |
| walkSpeedInitial | Float | `1` | Character's initial walk speed. |
| wallJumpLimit | Int | `0` | The number of wall jumps the character can perform. Use a negative number for infinite wall jumps. |
| wallJumpXSpeed | Float | `10` | The horizontal speed of a wall jump, positive values send the character away from the wall. |
| wallJumpYSpeed | Float | `10` | The vertical speed of a wall jump, positive values send the character upwards. |


