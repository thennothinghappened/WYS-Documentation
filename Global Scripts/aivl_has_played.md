## aivl_has_played(li_loca_keywords)

|Arg|Type|Description|
|:--|---|:--|
|li_loca_keywords|String|The localised line in question.|

### Returns: Boolean
### Example:
```gml
var line = "autodiff_down_first";
if (aivl_has_played(line)) {
    show_message(line + " has been played.");
}
```
This function returns true if a line of dialogue has already been played, or false if it has not.