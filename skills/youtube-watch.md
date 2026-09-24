---
name: youtube-watch
description: "Find and play a YouTube video, or open results to choose from"
platforms: [phone]
triggers: ["youtube", "youtube e", "video chalao", "video dekhao", "youtube pe"]
version: 1
updated: 2026-09-24
---

# youtube-watch

Find and play a YouTube video, or open results to choose from.
1. Clear request ("Tum Hi Ho video chalao") → `youtube` query, play=true.
2. Browsing ("cooking video dekhao") → `youtube` play=false; say the results are open.
3. If play=true came back with playing=false, say the reason from the result and offer
   to open the results instead.
4. Pause or next: `media`.

Never: tap an ad; say a video is playing when the result says it is not.
