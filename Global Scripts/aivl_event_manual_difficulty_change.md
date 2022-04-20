## aivl_event_manual_difficulty_change(diffchange)

|Arg|Type|Description|
|:--|---|:--|
|diffchange|Real|The change in difficulty to respond to.|

### Returns: N/A
### Example:
```gml
aivl_event_manual_difficulty_change(global.save_difficulty - difficulty_backup);
```
The above code is an exerpt from `obj_levelstyler_Step_0`. This function causes Squid to play a line about the player having manually changed the difficulty higher or lower and either agreeing or disagreeing with the choice.