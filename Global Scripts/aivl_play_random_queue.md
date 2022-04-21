## aivl_play_random_queue(li_loca_keywords, importance, iRandomEnd)

|Arg|Type|Description|
|:--|---|:--|
|li_loca_keywords|String|The localised line in question.|
|importance|Real|How important the line is compared to others.|
|iRandomEnd|Real|End point for `iRandomStart` when choosing a random version of the line.|

### Returns: Boolean
### Example:
```gml
aivl_play_random_queue("death_onconveyor_change", 3, 6);
```
The above code will choose a random variation between 1 and 6 of the line "death_onconveyer_change", with an importance of 3.
This function takes a line and an ending number, and chooses between 1 and `iRandomEnd` variations on the line by appending `_x` (`x` being the generated number) after the line name. This is identical to `aivl_play_random()` aside from setting `interrupt` to 2, instead of 0. This function runs `aivl_play_ext`, initialising the non-used arguments to:
- `li_script_start = -1`
- `li_script_end = -1`
- `interrupt = 2`
- `allow_more_than_once = false`