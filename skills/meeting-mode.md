---
name: meeting-mode
description: "Silence the phone for a meeting or class and bring sound back after"
platforms: [phone]
triggers: ["meeting", "meeting e achi", "silent koro", "class e achi"]
version: 1
updated: 2026-09-24
---

# meeting-mode

Silence the phone for a meeting or class and bring sound back after.
1. `phone_action` ringer_vibrate (ringer_silent if asked) and dnd_on.
2. Ask how long; `set_reminder` in_minutes "Meeting shesh — sound on korbo?".
3. Afterwards, when they say so: `phone_action` dnd_off and ringer_normal.
