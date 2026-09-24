---
name: app-navigator
description: "Do a task inside any app step by step using the screen"
platforms: [phone]
triggers: ["app e giye", "app mein jaake", "inside the app", "ei app e"]
version: 1
updated: 2026-09-24
---

# app-navigator

Do a task inside any app step by step using the screen.
Needs Accessibility: check `phone_action` accessibility_status; if off, offer
accessibility_settings.
1. `open_app`.
2. Loop: `read_screen` → choose one element → `tap_on_screen` with its index from the
   latest read, or `type_on_screen` (confirmed) → `read_screen` to check the change.
3. Not visible? `scroll_screen` down and read again, or use the app's own search box.
4. Stop and ask before anything that sends, buys, deletes or posts.
5. Finish by saying what was done, or exactly where it got stuck.
