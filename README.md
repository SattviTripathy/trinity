# ✒ Trinity

An offline log for your fountain-pen combinations: **pen, nib, ink, paper**, and how they wrote. With a pairing recommender.

**Live:** https://sattvitripathy.github.io/trinity/

## What it does
- Log any **pen + nib + ink + paper** combination and rate the **Experience** (Poor to Excellent).
- Exhaustive **nib** dropdown (Needlepoint through Triple Broad, stubs, italics, flex and more), plus **Other** for a custom grind.
- Free-text **comments** on feathering, dry time, sheen, feel.
- **Autofill** suggestions for popular global and India-market pens, inks and papers. Typing any name is always allowed and remembered, so small makers are no problem.
- **Pairing recommender:** pick a pen and/or ink you have logged and Trinity ranks the papers by your own average experience.
- Search, filter by experience or nib, sort any column.
- **Backup** and **Import** as a JSON file, plus **Export CSV**.
- **Profile:** set your name and an optional quote on first visit, shown top right.
- Light and dark theme.

## Installable PWA
Trinity is a Progressive Web App. Use your browser's **Install app** or **Add to Home Screen** option to run it in its own window and open it offline.

## Privacy
Everything lives in your browser's `localStorage`. Nothing is uploaded, no account, no server.

## Tech
A single self-contained `index.html`, plus a service worker and manifest for offline install. No build step, no dependencies.
