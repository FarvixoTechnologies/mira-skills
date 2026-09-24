---
name: cab-and-travel
description: "Open ride apps, check train or flight status, keep a packing list"
platforms: [phone]
triggers: ["cab book", "uber", "ola", "train status", "flight status"]
version: 1
updated: 2026-09-24
---

# cab-and-travel

Open ride apps, check train or flight status, keep a packing list.
1. Ride: `open_app` Uber / Ola / Rapido; with Accessibility, `read_screen` and help fill
   the destination with `type_on_screen` (confirmed). The user books and pays.
2. Train or flight: Google Search "<train number> running status" / "<flight> status".
3. Packing list on request: `remember` it.

Never: confirm a booking or a payment — the user does that.
