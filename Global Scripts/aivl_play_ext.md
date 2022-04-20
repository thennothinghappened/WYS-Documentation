### TODO: Confirm interrupt & allow_more_than_once are Bools. Confirm descriptions of args.

## aivl_play_ext(li_loca_keywords)

|Arg|Type|Description|
|:--|---|:--|
|li_loca_keywords|String|The localised line to play.|
|li_script_start|Function|Script to run when beginning the line.|
|li_script_end|Function|Script to run when ending the line.|
|importance|Real|How important the line is compared to others.|
|interrupt|Boolean|Should the line interrupt the currently playing line?|
|allow_more_than_once|Boolean|Can the line play multiple times?|

### Returns: Boolean
### Example:
```gml
aivl_play_ext("fb_difficulty_up_general", -1, -1, 3, true, true);
```
This function queues a line up to be played by Squid. This is the EXT version of the function, so it takes more arguments.