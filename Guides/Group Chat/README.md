## How to nail group chats on sillytavern?
This Isn't exactly a guide. most of the important stuff are available on other character creation guides, and ST DOCS. But people complaining on group chats not working for them the way they hoped is common, so I thought I'll write a few pointers that if you mind them, it can significantly improve the experience.
I'll be referring to a case of 3 group members in a chat group for simplicity (2 AI characters + a Human player ({{user}}), but mastering
that, makes adding more characters to the group simple because the core concepts remain the same..
so, diving right in, the following approach, should guarantee a better group chat experience:
### SCENARIO:
Make sure the characters you pick have no prefilled scenatio. If they do - Delete it. you'll be needing that block.
**Do not use the chat scenario override available in the group setting.** Sure, It solves the issue of having unrelated scenarios specified on each character card - but we already took care of it by deleting those (Or copy pasting them into the creator's notes - if you wish to keep those scenarios for later use).
#### Now comes the important part:
Whatever your scenario is. split it into 2 POVs, write the scenario for the first character from it's point of view, and the scenario for the second character from that second character's point of view. that's actually the most important part.
You'll achieve 2 goals:
1. For each character response generation, the output will be focused on that specific character's arc. -  so it's less likely to include other characters responses where it shouldnt)
2. Since it doesn't know what's in store for other characters, plotwise, when something happens, it's unexpected and the character will react more naturally and in line with it's personality.
**Example**:
If my explanation isn't clear, check out the following two cards to better understand what I mean by splitting a scenario into 2 POVs:
[Character_No.1](Character_No.1.md)
[Character_No.2](Character_No.2.md)

### Custom stopping strings:
Add every participating character's full name (do not use {{char}} placeholder. use the actual name) as a stopping string. for example, for a character named Mike: "\nMike:"
This way you won't experience that annoying situation where other characters respond before it's their turn to talk.


