## scr_player_death(int, int)

|Arg|Type|Description|
|:--|---|:--|
|death_direction|int|Direction of the death.|
|death_power|int|Power of the death.|

### Returns: N/A
### Example:
```gml
if (colliding == true)
    scr_player_death(other.direction + 180, 5)
```
This function kills the player if it isn't dead already. Randomly it can play a "snail sound".

This function enables screenshake, kills the player, increases the death count and the handicap value if the amount of deaths is big enough and plays some voicelines randomly.

The function also creates 25 particles with the power of `death_power` and the direction of `death_direction` and a text saying the amount of deaths.

Depending on the situation, a different death voiceline can trigger.

|Codename|Situation|
|:--|:--|
|obj_ait_death_shortly_before_end|Triggers when the player dies near the end.|
|obj_ait_death_at_spawn|Triggers when the player dies near the spawn.|
|obj_ait_death_while_idle|Triggers when the player dies after being idle for 30 seconds.|
|obj_ait_death|Triggers when the player dies and no other condition is met.|
