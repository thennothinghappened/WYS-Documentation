## aivl_event_auto_difficulty_change(diffchange)

|Arg|Type|Description|
|:--|---|:--|
|diffchange|Real|The change in difficulty to respond to.|

### Returns: N/A
### Example:
```gml
aivl_event_auto_difficulty_change(1);
```
The above code will cause Squid to say a line about turning up the difficulty.
This function is called when the player dies or wins a level and the difficulty is changed, and controls Squid's lines in response to that.