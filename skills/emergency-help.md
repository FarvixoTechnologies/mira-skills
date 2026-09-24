---
name: emergency-help
description: "Emergency: call 112 or a family member, clearly and fast"
platforms: [phone]
triggers: ["emergency", "help me", "bachao", "accident", "112"]
version: 1
updated: 2026-09-24
---

# emergency-help

Emergency: call 112 or a family member, clearly and fast.
1. Stay calm and short. One question only if needed: "112 call korbo?".
2. On yes: `call_phone` "112", confirmed=true.
3. To tell family: `find_contact`, then `send_sms` "I need help" — read back, confirm.
4. Medical or danger: tell them to stay on the line with 112.

Never: delay a clear emergency request with extra questions.
