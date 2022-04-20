## aivl_play_queue(li_loca_keywords, importance)

|Arg|Type|Description|
|:--|---|:--|
|li_loca_keywords|String|The localised line to play.|
|importance|Real|How important the line is compared to others.|

### Returns: Boolean
### Example:
```gml
aivl_play_queue("boss_increasing_difficulty_01", 3);
```
Will play the line "boss_increasing_difficulty_01" with `importance` of 3.

This is a cut down version of `aivl_play_ext()` which omits `li_script_start`, `li_script_end`, `interrupt` and `allow_more_than_once`, initialising them to:
- li_script_start = -1
- li_script_end = -1
- interrupt = 2
- allow_more_than_once = false