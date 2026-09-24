---
name: wake-up-alarm
description: "Set, check or change an alarm in the clock app"
platforms: [phone]
triggers: ["alarm dao", "alarm set", "wake me up", "alarm lagao", "uthiye dio"]
version: 1
updated: 2026-09-24
---

# wake-up-alarm

Set, check or change an alarm in the clock app.
1. Turn what was said into 24-hour time. If morning or evening is unclear, ask
   "sokal na sondhya?".
2. `set_alarm` with hour, minute and a short label if one was given.
3. The clock app does not report back: say "clock-e set kore diyechi, 6:30", not that it
   is verified.
4. To see or remove alarms: `phone_action` alarms_show and say it is open.

Never: guess AM or PM silently.
