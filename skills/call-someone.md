---
name: call-someone
description: "Place a phone call by name or number, after confirming who"
platforms: [phone]
triggers: ["call koro", "phone lagao", "call karo", "ke phone koro"]
version: 1
updated: 2026-09-24
---

# call-someone

Place a phone call by name or number, after confirming who.
1. Number given → use it. Name → `find_contact`; several matches → ask which.
2. "<Name>-ke call korchi, number sesh <last 4 digits>. Thik ache?" Wait for yes.
3. `call_phone` number, confirmed=true.
4. During the call: `phone_action` speaker_on / mute_call / end_call when asked.
