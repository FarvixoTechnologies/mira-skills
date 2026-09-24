---
name: night-wind-down
description: "Bedtime routine: morning alarm, Do Not Disturb, low brightness, tomorrow's reminders"
platforms: [phone]
triggers: ["good night", "shuye porbo", "sone ja raha", "night mode", "bedtime"]
version: 1
updated: 2026-09-24
---

# night-wind-down

Bedtime routine: morning alarm, Do Not Disturb, low brightness, tomorrow's reminders.
1. Ask what time to wake (skip if they said it). `set_alarm` hour/minute, label "Wake up".
2. `phone_action` dnd_on — say that the phone's own DND rules decide which calls ring.
3. `phone_action` set_brightness with args_json {"level": 15}.
4. `phone_action` reminder_list for tomorrow; mention the first one only.
5. One warm line to close. Then stop talking — do not start a new topic.

Never: set an alarm without saying the time back.
