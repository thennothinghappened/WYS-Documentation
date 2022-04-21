### TODO: What does importance do?

## aivl_play(li_loca_keywords, importance)

|Arg|Type|Description|
|:--|---|:--|
|li_loca_keywords|String|The localised line to play.|
|importance|Real|How important the line is compared to others.|

### Returns: Boolean
### Example:
```gml
aivl_play("fb_difficulty_up_general", 3);
```
This function queues a line up to be played by Squid. This is a cut down function that calls `aivl_play_ext()` with the default parameters:
- `li_script_start = -1`
- `li_script_end = -1`
- `interrupt = 0`
- `allow_more_than_once = false`