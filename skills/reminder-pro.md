---
name: reminder-pro
description: "Reminders that survive reboots: one-off, repeating, snooze and cancel"
platforms: [phone]
triggers: ["remind me", "mone koriye dio", "yaad dilana", "reminder dao", "reminder set"]
version: 1
updated: 2026-09-24
---

# reminder-pro

Reminders that survive reboots: one-off, repeating, snooze and cancel.
1. Pull out WHAT and WHEN. Relative ("20 minute por") → `set_reminder` in_minutes.
   Clock time ("rat 9 ta") → `set_reminder` at "21:00".
2. Repeating ("roj", "every Monday"): set it and say how it repeats.
3. List: `phone_action` reminder_list. Cancel: read the list, confirm which one, then
   `phone_action` reminder_cancel with confirmed=true. Snooze: reminder_snooze.

Never: cancel a reminder without naming it back first.
