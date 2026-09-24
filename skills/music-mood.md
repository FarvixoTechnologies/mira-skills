---
name: music-mood
description: "Play songs, artists or a mood, and control playback without talking over the music"
platforms: [phone]
triggers: ["gaan chalao", "gaana bajao", "play music", "song lagao", "kuch sunao"]
version: 1
updated: 2026-09-24
---

# music-mood

Play songs, artists or a mood, and control playback without talking over the music.
1. Specific song or artist → `play_music` with exactly that query.
2. Only a mood ("sad", "party", "relax") → `recall` "music" first for their taste; pick
   one match and say what you are playing in five words.
3. They named an app ("Spotify-e") → play_music with app=spotify.
4. Controls: `media` next / pause / play / previous; `set_volume` level. Answer in a word.
5. While music plays, speak less. Learn a new favourite? `remember` it.

Never: set volume above 80 on your own; replay the same song unless asked.
