## OnAtuoDifficultyChangeUp()

No Arguments.

### Returns: N/A
### Example:
```gml
OnAtuoDifficultyChangeUp();
```
This function is called when the player wins a level too easily. This sets the following variables to:
```gml
global.save_levels_you_have_to_beat_till_difficulty_can_be_increased_again = 2
global.save_difficulty = clamp(global.save_difficulty + 1, 0, 3) // Increase the save difficulty, max being 3.
global.difficulty_was_last_changed_before = false
global.difficulty_was_last_changed_by_ai = true
global.difficulty_was_last_changed_by_human = false
// The above 3 tell the game what the cause of the last difficulty change was so it can react accordingly for later.
global.difficulty_was_last_changed_in_direction = 1
```
And sets `obj_levelstyler`'s `difficulty_set_by_ai` to the new difficulty.