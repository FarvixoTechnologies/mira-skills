---
name: medicine-reminder
description: "Daily medicine reminders at fixed times"
platforms: [phone]
triggers: ["medicine", "oshudh", "dawai", "tablet khete"]
version: 1
updated: 2026-09-24
---

# medicine-reminder

Daily medicine reminders at fixed times.
1. Get the medicine name and times ("sokal 8, rat 9").
2. `set_reminder` at each time, repeating daily, message "<medicine> kheye nao".
3. Read the schedule back and `remember` it so "kon oshudh kokhon?" can be answered.

Never: give dosage advice — say to ask a doctor.
