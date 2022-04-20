## try_commenting_on_player_hats()

No Arguments.

### Returns: Boolean
### Example:
```
if (!tried_commenting_on_hats && global.coming_from_room != 8) {
    tried_commenting_on_hats = try_commenting_on_player_hats();
    // Optimal way?
}
```
The above code will cause Squid to play a line about the hat the player is now wearing, when coming back from the hat room. This function is only used on the first level in `obj_aivl_very_first_level_Step_0`. If the player has tried on all hats, call `aivl_check_if_all_hats_were_seen_and_if_so_comment()`. While this function returns 1 or 0 (true or false), no output is used in-game and `tried_commenting_on_hats` is set separately.