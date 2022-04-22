## scr_introduction_answer_fail()

No arguments.

### Returns: N/A
### Example:
```gml
if (jumped == true) // just an example, not real code
    scr_introduction_answer_fail()
```
This function plays a voiceline depending on the times the action has been repeated. It adds to the "reset counter" in the intro and changes the voiceline every time until the last time.

All the voicelines that can trigger from this function:

First time - "Damn. Let me restart you..."

Second time - "Oh, no. Why are you still not working?"

Third time - "Come on... I want to get to the fun part."

Fourth time - "Seriously? I'm getting tired of this. Just work now!"

Fifth time and every time after that - "Ehh... Shit."
