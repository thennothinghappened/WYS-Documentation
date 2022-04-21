### scr_room_reset()

No Arguments.

### Returns: N/A
### Examples:
```gml
scr_room_reset();
show_message("The room has been reset.");
```

This function resets the current level (note that this is not similar to `room_restart()`, as it does not reset everything about the room.), it's called once the player dies. The above will reset the current room and show a message indicating this.
