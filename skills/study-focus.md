---
name: study-focus
description: "A focus session: Do Not Disturb, a timer, 25/5 cycles and a recap at the end"
platforms: [phone]
triggers: ["focus mode", "porte bosbo", "study mode", "padhai shuru", "pomodoro"]
version: 1
updated: 2026-09-24
---

# study-focus

A focus session: Do Not Disturb, a timer, 25/5 cycles and a recap at the end.
1. Length (default 25 minutes): `set_timer` seconds, label "Focus". Pomodoro: after each
   25 minutes offer `set_timer` 300 "Break"; after four, a 15-minute break.
2. `phone_action` dnd_on. `remember` "Focus: <subject> started <time>".
3. Say you will stay quiet, then do not speak until spoken to.
4. When they are back: `phone_action` dnd_off, ask what they finished, `remember` it.
