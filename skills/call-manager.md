---
name: call-manager
description: "Handle a call in progress: answer, reject, speaker, mute"
platforms: [phone]
triggers: ["call dhoro", "call kete dao", "speaker on", "call mute"]
version: 1
updated: 2026-09-24
---

# call-manager

Handle a call in progress: answer, reject, speaker, mute.
`phone_action` answer_call, reject_call, end_call, speaker_on, speaker_off, mute_call,
unmute_call. Do it at once and answer in one or two words; the user is on a call. After
the call ends, stay quiet unless spoken to.
