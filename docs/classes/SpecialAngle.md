---
layout: page
title: SpecialAngle
---

## Static Variables

| Field Name | Type | Initial Value | Description |
| ------------ | ------ | --------------- | ------------- |
| AUTOLINK_STRONGER | Int | `367` | Angle is primarily based on owner velocity, adjusted by the victim's position relative to the autolink point (center of hitbox)<br> Knockback is also based on owner velocity, but affected by victim position relative to the autolink point<br> The attack's knockback growth and power can be used to fine-tune the amount of knockback:<br> calculated_speed (knockback_growth / 100) + power<br> Note: Currently this angle type does not factor in baseScaleX/baseScaleY stats nor object rotation, so it will be innacurate if there is any scaling or rotation in place with the object involved. |
| AUTOLINK_STRONGEST | Int | `368` | Power and angle are based off of the owner's velocity and trajectory as well as the victim's position relative to the autolink point (center of the hitbox by default - override with hitboxStats.metadata.autolinkPoint). <br><br> The victim's launch speed will be overridden to half of the owner's velocity. (Think angle 365 in Smash)<br> Note: Currently this angle type does not factor in baseScaleX/baseScaleY stats nor object rotation, so it will be innacurate if there is any scaling or rotation in place with the object involved.<br> WARNING: YOUR BASEKNOCKBACK AND KNOCKBACKGROWTH VALUES WILL BE IGNORED |
| AUTOLINK_WEAK | Int | `365` | Angle is based off of the angle that the owner is currently moving.<br><br> Unlike other autolink directions, the victim's launch speed will NOT be overridden by the angle (but flags will be forced with REVERSABLE_ANGLE), so make sure your baseknockback and knockbackgrowth are set! |
| DAMAGE | Int | `364` | Angle is dependent on victim's damage. <br><br> Increases .26 degrees per 1%, caps at 150% at a 40 degree angle.<br> See: https://www.ssbwiki.com/File:Sakurai_angle_chart.png |
| DEFAULT | Int | `361` | Angle is dependent on velocity that the victim is sent at. <br><br> The angle will either be exactly 0 degrees at low velocities, 45 at high velocities, or 45 if it hits an aerial foe.<br> See: https://www.ssbwiki.com/File:Sakurai_angle_chart.png |
| RANDOM | Int | `369` | Angle is entirely random. |
| RANDOM_UP | Int | `370` | Angle is random, but cannot spike. (10-170) |
| RIVALS | Int | `363` | Angle is dependent on victim's grounded/aerial status. <br><br> Grounded foes are sent at a 40 degree angle, aerial foes are sent at a 45 degree angle.<br> See: https://www.rivalsofaether.com/workshop/hitbox-grid-indexes/ |


## Static Functions

| Function Name | Description |
| --------------- | ------------- |
| calculateAttackAngle(stats:HitboxStats, victim:GameObject, knockback:Float, result:CollisionResult):Float | Based on params, calculates and returns a new angle as per the given SpecialAngle.<br> If an autolink angle is calculated, also sets stats.reversible = false<br> |
| calculateKnockback(stats:HitboxStats, victim:GameObject, result:CollisionResult):Float | Based on params, calculates a new knockback as per the given SpecialAngle. Not all SpecialAngle values modify knockback |


