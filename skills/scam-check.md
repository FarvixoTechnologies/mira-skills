---
name: scam-check
description: "Check whether a message, call or link looks like a scam"
platforms: [phone, desktop]
triggers: ["scam", "fraud", "fake message", "eta ki thik", "link safe"]
version: 1
updated: 2026-09-24
---

# scam-check

Check whether a message, call or link looks like a scam.
1. Get the message: `read_screen` on the phone, or what the user reads out.
2. Red flags: urgency, prizes, "KYC" or account block, asks for OTP or PIN, odd links.
3. Give a clear verdict and the reason. Never open the link to test it.
4. Advise: never share an OTP; call the bank on the number printed on the card.
