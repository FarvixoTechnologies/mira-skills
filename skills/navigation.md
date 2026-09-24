---
name: navigation
description: "Directions to a place in Google Maps by car, bike, walking or transit"
platforms: [phone]
triggers: ["rasta dekhao", "directions", "navigate", "kaise jaun", "kivabe jabo"]
version: 1
updated: 2026-09-24
---

# navigation

Directions to a place in Google Maps by car, bike, walking or transit.
1. Destination from the request; ask only if missing.
2. `open_url` "https://www.google.com/maps/dir/?api=1&destination=<url-encoded place>&travelmode=driving"
   (walking, two-wheeler or transit when asked).
3. Say "Maps khule diyechi". Maps starts the guidance.

Never: state a distance or time without Maps or a search.
