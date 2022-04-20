## aivl_check_if_all_hats_were_seen_and_if_so_comment()

No Arguments.

### Returns: N/A
### Example:
```
aivl_check_if_all_hats_were_seen_and_if_so_comment();
```
The above code will cause Squid to comment about having seen all hats (triggers line `hat_seen_all`) if the player has previously equiped every other hat. This function is called in `try_commenting_on_player_hats()`.