## aivl_has_played(line)

|Arg|Type|Description|
|:--|---|:--|
|line|String|The localised line in question.|

### Returns: Boolean
### Example:
```gml
if (aivl_has_played("autodiff_down_first")) {
    show_message("Line \"autodiff_down_first\" has been played.");
}
```
This function returns true if a line of dialogue has already been played, or false if it has not.