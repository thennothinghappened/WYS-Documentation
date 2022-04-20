## scr_fade_to_room_ext
|Arg|Type|Description|
|:--|---|:--|
|room_name|String|The name of the room to fade to|
|is_shortcut|Boolean|If the specified room is a shortcut|
### Returns: N/A
### Example:
```gml
scr_fade_to_room_ext(T_01_first_contact, true);
```
This function is called when you complete a level to fade into the next level (or the level specified in the function call) with another parameter which is
if the room is a shortcut.

