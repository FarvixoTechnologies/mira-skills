---
name: macro-builder
description: "Record a repeated task once and replay it by name"
platforms: [phone]
triggers: ["macro", "record koro", "shortcut banao", "repeat task"]
version: 1
updated: 2026-09-24
---

# macro-builder

Record a repeated task once and replay it by name.
Record: `phone_action` macro_record_start {"name": "<name>"}; the user does the task;
then `phone_action` macro_record_stop. Say how many steps were saved. Run: `run_macro`
name, confirmed=true after naming it back. List: `list_macros`. Recording needs
Accessibility.
