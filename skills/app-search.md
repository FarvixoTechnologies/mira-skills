---
name: app-search
description: "Search inside an app: Play Store, Amazon, Flipkart, Instagram and others"
platforms: [phone]
triggers: ["search koro", "khojo", "dhundo", "search in"]
version: 1
updated: 2026-09-24
---

# app-search

Search inside an app: Play Store, Amazon, Flipkart, Instagram and others.
1. `open_app`, `read_screen`, tap the search box ("Search" or the magnifier icon).
2. Say the query back, then `type_on_screen` it with confirmed=true.
3. `phone_action` screen_wait with {"text": "<query>"}, `read_screen`, and describe the top
   three results.
