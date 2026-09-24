---
name: display-comfort
description: "Brightness, auto-brightness, rotation and screen timeout"
platforms: [phone]
triggers: ["brightness", "alo kom", "screen bright", "rotation", "screen timeout"]
version: 1
updated: 2026-09-24
---

# display-comfort

Brightness, auto-brightness, rotation and screen timeout.
`phone_action` set_brightness {"level": 0-100}, brightness_up / brightness_down,
auto_brightness_on / off, rotation_on / off, screen_timeout {"seconds": n}. These need
"Modify system settings"; if refused, say so and point to MIRA Settings → Permissions.
