---
name: screen-explainer
description: "Explain what is on the screen, read it aloud, or summarise a long page"
platforms: [phone]
triggers: ["screen e ki ache", "what's on my screen", "eta ki", "pore shunao"]
version: 1
updated: 2026-09-24
---

# screen-explainer

Explain what is on the screen, read it aloud, or summarise a long page.
1. `read_screen`. Summarise in two or three sentences, most important first.
2. "Pore shunao" → read the main text in order, skipping menus and buttons.
3. Long page → `scroll_screen` down and `read_screen` again, at most five times.

Never: read out passwords, OTPs or card numbers even if visible.
