## scr_introduction_answer_fail()

No arguments.

### Returns: N/A
### Example:
```gml
if (jumped == true) // just an example, not real code
    scr_introduction_answer_fail()
```
This function plays a voiceline depending on the times the action has been repeated. It adds to the "reset counter" in the intro and changes the voiceline every time until the last time.

All the voiceline code:
```gml
if (global.save_restarts_by_ai_in_tutorial == 0)
{
    ds_list_add(list_strings, "Damn. Let me restart you...")
    ds_list_add(list_sounds, 97)
}
else if (global.save_restarts_by_ai_in_tutorial == 1)
{
    ds_list_add(list_strings, "Oh, no. Why are you still not working?")
    ds_list_add(list_sounds, 51)
}
else if (global.save_restarts_by_ai_in_tutorial == 2)
{
    ds_list_add(list_strings, "Come on... I want to get to the fun part.")
    ds_list_add(list_sounds, 52)
}
else if (global.save_restarts_by_ai_in_tutorial == 3)
{
    ds_list_add(list_strings, "Seriously? I'm getting tired of this. Just work now!")
    ds_list_add(list_sounds, 53)
}
else
{
    ds_list_add(list_strings, "Ehh... Shit.")
    ds_list_add(list_sounds, 54)
}
```
