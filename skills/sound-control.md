---
name: sound-control
description: "Volume, ringer mode, Do Not Disturb, alarm and ring volume"
platforms: [phone]
triggers: ["volume", "awaj", "awaaz", "vibrate", "dnd"]
version: 1
updated: 2026-09-24
---

# sound-control

Volume, ringer mode, Do Not Disturb, alarm and ring volume.
Media: `set_volume`. Ring or alarm: `phone_action` set_ring_volume / set_alarm_volume
{"level": n}. Modes: ringer_silent / ringer_vibrate / ringer_normal, dnd_on / dnd_off.
Answer in one or two words.
