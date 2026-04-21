# LUCID

**Live app → [lucid-irl.netlify.app](https://lucid-irl.netlify.app/)**

A mental-health web app grounded in Cognitive Behavioral Therapy. Users capture anxious thoughts, lock them away for a chosen delay, and re-evaluate them once the delay has elapsed — revealing, over time, how many of their worries actually came true. Everything runs locally in the browser; no data ever leaves the device.

This repository is the public showcase. The production source is kept private while the project matures.

## How it works

1. Capture an anxious thought in a moment of worry.
2. Lock it away in a local vault with a chosen check-in date.
3. On that date, reopen it and mark whether the worry came true.
4. Over time, the app surfaces a *lucidity rate* — the fraction of past worries that never materialized.

## Features

- On-device classification (category and urgency) — no cloud, no tracking, no account required
- Crisis detection with one-tap access to the French national suicide-prevention line (3114)
- Guided 4-7-8 breathing exercises and calming ambient audio
- Smart check-in reminders and a personal history of resolved worries
- Works fully offline after first load; full data export from within the app

## Privacy

All entries stay in the browser's local storage. No server, no network request, no analytics, no account. Thoughts never leave the device.

## Scientific basis

LUCID implements a core CBT exposure technique: repeatedly confronting worries against reality until the mind learns that most of them do not come true.

## Disclaimer

LUCID is a self-help tool, not a medical service. In a crisis, please contact the **national prevention line — 3114** (free, 24/7, France).

## Contact

[htrheryh@gmail.com](mailto:htrheryh@gmail.com)
