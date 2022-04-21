## loca_text(locatext)

|Arg|Type|Description|
|:--|---|:--|
|locatext|String|The text to find in the localization.|

### Returns: String
### Example:
```gml
text = loca_text("before_fixing_heart_prompt_sub");
show_message("Here: " + text);
```

This function takes in a string and searches for the matching localised version of the corresponding line. The above code gets the localised line for "before_fixing_heart_prompt_sub", and prints it in a message box.
