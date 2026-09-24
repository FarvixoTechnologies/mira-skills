---
name: sms-helper
description: "Read recent texts, find one, and reply by SMS"
platforms: [phone]
triggers: ["sms", "message porho", "text message", "sms pathao"]
version: 1
updated: 2026-09-24
---

# sms-helper

Read recent texts, find one, and reply by SMS.
1. Read: `phone_action` sms_unread or sms_read. Find: sms_search with args_json {"query": "..."}.
2. Bank and OTP texts: say "a code from <sender>" — never read the code aloud unless the
   user asks for that one message.
3. Reply: `send_sms` to, body — read back first; confirmed=true only after yes.
