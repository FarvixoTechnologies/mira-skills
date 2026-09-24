# MIRA Skills

The skill store for **MIRA** — the phone assistant and MIRA Core on the desktop — by
Farvixo Technologies.

A skill is a **playbook**: when a request fits it, which MIRA tools to use in what order,
and what never to do. MIRA's Live voice loads one with `use_skill` when the topic comes up;
MIRA Core shows matching ones to its planner.

A skill grants nothing. Every call it suggests still goes through MIRA Rules, the
lock-screen settings and the confirmation step for calls, messages and typing.

## Layout

```
index.json          every skill: name, description, platforms, triggers, file, sha256
skills/<name>.md    the playbook, with front matter
```

The app and Core verify each file against the SHA-256 in `index.json` and install the set
only when all of it matches.

## Getting them

- **Phone:** Settings → Skills → **Refresh**. All fifty also ship inside the app.
- **Desktop:** `mira skills pull` (and `mira skills list`).

## Skills (50)

| Area | Skills |
|---|---|
| Day | daily-briefing, night-wind-down, wake-up-alarm, quick-timer, reminder-pro |
| Music & video | music-mood, youtube-watch |
| People | whatsapp-message, whatsapp-catch-up, call-someone, missed-calls, sms-helper, call-manager |
| Camera & screen | photo-to-whatsapp, screen-explainer |
| Getting around | navigation, nearby-places, driving-companion, cab-and-travel |
| Information | weather-check, news-headlines, sports-scores, market-watch, currency-and-units, translate-speak, homework-helper |
| Focus & health | study-focus, meeting-mode, water-reminder, medicine-reminder, workout-coach |
| Phone care | phone-care, connectivity-help, display-comfort, sound-control, quick-toggles |
| Notes | quick-notes, shopping-list, birthdays-and-dates |
| Inside apps | app-navigator, app-search, form-filler, clipboard-helper, macro-builder |
| Safety | emergency-help, scam-check |
| Desktop | pc-launch, pc-research, pc-files, pc-health |

## Contributing

Skills are generated from `scripts/skills/skill_sources.py` in the MIRA repository. The
build refuses any playbook that names a tool MIRA does not have, so edit the source there
and rebuild rather than editing these files by hand.
