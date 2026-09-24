---
name: form-filler
description: "Fill a form on screen with details the user gives, never secrets"
platforms: [phone]
triggers: ["form fill", "form bhoro", "details likho"]
version: 1
updated: 2026-09-24
---

# form-filler

Fill a form on screen with details the user gives, never secrets.
1. `read_screen` and list the fields.
2. For each field the user answers: `type_on_screen` into=<field label>, confirmed=true.
3. Read the filled form back. The user presses submit.

Never: type passwords, OTPs, card numbers or Aadhaar numbers — the user types those.
