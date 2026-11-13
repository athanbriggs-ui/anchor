# Anchor

A personal ADHD support app. Plain HTML/JS, no build step, no accounts, no server. All data stays in the browser on your device.

## Put it on your phone (GitHub Pages)

1. Push this folder to a GitHub repo.
2. Repo → Settings → Pages → Source: "Deploy from a branch" → `main` / root.
3. Open the Pages URL on your phone.
4. iPhone: Share → "Add to Home Screen". Android: menu → "Install app".

## What's in it

- **Today**: max 3 must-dos, each shown as one tiny next step. "I'm stuck" and "Wheels fell off" buttons.
- **Focus**: shrinking-pie visual timer, time-passing chimes, body-double shortcuts.
- **Plan**: appointments with automatic buffer and a "leave by" time; export to Google Calendar or an `.ics` file with three alarms. Habit stacks ("When X, I will Y").
- **Dump**: quick capture from any screen (the ✎ button).
- **Support**: your encourager's contact, finance/notification guardrail checklist, wins log, backup/restore.

## Run locally

```bash
python3 -m http.server 8000
```
