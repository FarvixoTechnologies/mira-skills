---
name: daily-briefing
description: "Good morning briefing: time, weather, battery, reminders, notifications and top news in one short answer"
platforms: [phone]
triggers: ["good morning", "din ka update", "aajker update", "morning briefing", "subah ka update"]
version: 1
updated: 2026-09-24
---

# daily-briefing

Good morning briefing: time, weather, battery, reminders, notifications and top news in one short answer.
Say it as one short spoken briefing, not a list read aloud.

1. Greet once, using the date and time you were given.
2. Weather: Google Search "weather today <user's city>" (ask the city once if unknown,
   then `remember` it). One line: temperature, rain chance.
3. `battery_status` — mention it only if under 30% or charging.
4. `phone_action` action=reminder_list — today's reminders, at most three.
5. `read_notifications` — count by app, name people and apps only; never read private
   message text aloud unless the user asks.
6. Google Search "top news India today" — two headlines, one line each.
7. End with one question: "Aaj ki plan?" — nothing more.

Never: read OTPs or bank messages aloud; invent weather or news without searching.
