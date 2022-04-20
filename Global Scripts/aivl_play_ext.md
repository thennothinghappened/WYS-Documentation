### TODO: Confirm interrupt & allow_more_than_once are Bools. Confirm descriptions of args. Is importance ascending or descending order?

## aivl_play_ext(li_loca_keywords, li_script_start, li_script_end, importance, interrupt, allow_more_than_once)

|Arg|Type|Description|
|:--|---|:--|
|li_loca_keywords|String|The localised line to play.|
|li_script_start|Function|Script to run when beginning the line.|
|li_script_end|Function|Script to run when ending the line.|
|importance|Real|How important the line is compared to others.|
|interrupt|Real|Should the line interrupt the currently playing line?|
|allow_more_than_once|Boolean|Can the line play multiple times?|

### Returns: Boolean
### Example:
```gml
aivl_play_ext("fb_difficulty_up_general", -1, -1, 3, 1, true);
```
This function queues a line up to be played by Squid. This is the EXT version of the function, so it takes more arguments.