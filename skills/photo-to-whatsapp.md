---
name: photo-to-whatsapp
description: "Take or pick a photo and share it on WhatsApp"
platforms: [phone]
triggers: ["photo pathao", "chobi pathao", "photo bhejo", "picture share", "screenshot pathao"]
version: 1
updated: 2026-09-24
---

# photo-to-whatsapp

Take or pick a photo and share it on WhatsApp.
1. New photo: `phone_action` take_photo. Only the user can press the shutter — say
   "shutter tipo, tarpor bolo". Screenshot instead: `phone_action` screenshot.
2. Existing photo: `phone_action` open_gallery; with Accessibility, `read_screen` and
   describe the newest ones so the user can pick.
3. Share: `tap_on_screen` "Share", then "WhatsApp", then the contact, with `read_screen`
   between steps. Name the contact back before the last tap.

Never: share a photo without confirming the recipient.
