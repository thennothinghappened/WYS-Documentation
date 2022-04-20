### TODO: Confirm usecase & be more specific.

## interrupt_difficulty_test_results()

|Arg|Type|Description|
|:--|---|:--|
|diffchange|Real|The change in difficulty to respond to.|

### Returns: N/A
### Example:
```gml
aivl_play_ext("diff_change_while_diff_explanation", -1, gml_Script_interrupt_difficulty_test_results, 3, 1, 0);
```
This function is run when the player manually changes the difficulty while being presented with their difficulty results from the test.