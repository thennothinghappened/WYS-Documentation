
### TODO: Maybe explain level types & others

## scr_level_dat_add(room_id, lvl_type, lvl_icon, lvl_name, unlock_levels, lvl_isboss, lvl_chapter, lvl_exploration_points, lvl_limitedbuild_available)

|Arg|Type|Description|
|:--|---|:--|
|room_id|Real|The room ID of the level.|
|lvl_type|Real|The type of level it is.|
|lvl_icon|Real|The sprite index for the icon.|
|lvl_name|Real|The name of the level.|
|unlock_levels|Array|An array containing the levels unlocked when entering. Can be left empty.|
|lvl_isboss|Boolean|True if the level is a boss level.|
|lvl_chapter|Real|The chapter the level appears in.|
|lvl_exploration_points|Array|An array containing all of the exploration points obtainable in the level.|
|lvl_limitedbuild_available|Boolean|True if it is available in a limited build.|

### Returns: N/A
### Example:
```gml
scr_level_dat_add(30, 4, 344, "A01.1", [34], false, 1, ["SecretPassage"], true)
```
The above code will add room 30 to the level id data, set the level type to 4, set the level icon to the sprite indexed 344, set the level name to A01.1, set level id 34 to be unlocked when entering, sets the level to not be a boss level, sets the chapter to chapter A, sets the exploration point "SecretPassage" to be obtainable in the level, and allows the level to be enabled in a limited build.
This function is mainly used in ``scr_level_dat_ini``.
