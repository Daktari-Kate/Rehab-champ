# Rehab Champ

A private companion app for recovering from an Achilles tendon rupture. It tells you what today's rehab session is, makes logging it quick, and shows your progress across a 12-month recovery.

> We're sorry you need this app. We know it's a long, slow recovery, and faithful rehab makes all the difference. You've got one shot at getting this right, so Rehab Champ is here to cheer you on.

<!-- Edit this file on github.com and drag Rehab-Champ-intro-for-GitHub.mp4 here to embed the intro video. -->
https://github.com/Daktari-Kate/Rehab-champ/blob/main/Rehab-Champ-intro-for-GitHub.mp4

**Open the app:** https://daktari-kate.github.io/rehab-champ/

## What it does

- **Today** shows what's due, grouped by time of day. Tap an exercise to tick it off; weights are remembered.
- **Weekly planning**: at the start of each week, choose which days you do gym, pool and other sessions. They only appear on those days. You can plan next week from Saturday.
- **Physio clearance**: sessions such as running, plyometrics and pool stay hidden until you enter the date your physio clears them.
- **Goal sports**: add the sports you're working back to, each with a staged return-to-sport checklist.
- **Progress**: weekly adherence, a calendar of every session, milestones and key dates.
- **Daily check-in** for pain and swelling, plus an evening check-in for steps and body weight.
- Works for a **left or right** Achilles, in **kg or lbs**.
- **Backup and restore** of your data from Settings.

## Install on an iPhone

1. Open the app link in **Safari** (not Chrome or an in-app browser).
2. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
3. Open it from the new icon **with internet on** the first time, so it can work offline afterwards.

Please don't delete the home-screen icon to "reinstall" the app. On iPhone that erases your logged data. Updates arrive on their own.

## Privacy by design

All your data stays on your phone. There are no accounts, no servers and no analytics, and nothing is sent anywhere. This repository contains only the app itself and a generic exercise program, never anyone's logs. Back up your data from Settings now and then, because it exists only on your device.

The in-app "Send feedback" button opens an email that you can read and edit before sending it yourself.

## Important: not medical advice

The built-in program follows one physiotherapist's plan. Rehab Champ is not a substitute for professional care. Confirm every phase, exercise and clearance with your own physiotherapist or surgeon, and change the program to match their advice. Moving to the next phase is always your decision with your physio; the app never advances it for you.

## About

Rehab Champ was designed by Dr Kate Taylor when she injured her Achilles. She is a digital health founder, so the app is built on clinical evidence and best practice, but you tailor the program based on your physiotherapist's advice.

## For developers

A single-page progressive web app: one `index.html`, a web manifest, a service worker for offline use and two icons. There is no build step and no dependencies. Data is stored in the browser's `localStorage`, with all weights stored in kg. It is hosted with GitHub Pages.
