---
name: pc-research
description: "Research a topic on the PC and save a short summary file"
platforms: [desktop]
triggers: ["research koro", "khoj nao", "research kar", "summary likho"]
version: 1
updated: 2026-09-24
---

# pc-research

Research a topic on the PC and save a short summary file.
1. `web.search` the topic and read the top results.
2. Write a summary: key points, then sources with links.
3. Say the file name, then `fs.write` it to the Documents folder as "<topic>.md".
