# SORI (소리) — Korean Music, Decoded

A prototype web app that introduces Korean traditional music (gugak) to international fans — tourists, K-drama fans, and Korean learners — and takes them from "I saw this on Reels" to actually sitting in a Seoul theater.

**Working title.** MVP prototype, v0.1.

## What's inside

- **Explore** — friendly English intros to six sounds: pansori, haegeum, gayageum, minyo, samulnori, daegeum
- **Lyrics pilot** — Simcheongga's famous *Beompi jungnyu* passage, decoded line by line (original text, romanization, translation, cultural commentary) with a tap-to-open glossary
- **Shows** — real, verified Seoul performances with prices, English-subtitle info, and exactly how to book (National Gugak Center, Jeongdong Theater, Yeowoorak Festival, Korea House, Jinyeon)
- **Learn** — real classes and workshops open to non-Koreans, plus a teacher-matching request (mock)
- **Taste-based recommendations** — pick your vibe, show rankings update live

## Stack

Single static `index.html` — no build step, no dependencies, vanilla JS. Light/dark theme via `prefers-color-scheme`.

## Run locally

Open `index.html` in a browser. That's it.

## Deploy

Any static host works. For Vercel: import this repo at [vercel.com/new](https://vercel.com/new) — no configuration needed.

## Roadmap (post-pilot)

- More decoded passages (voted on in-app)
- ElevenLabs voice features (real-time translation of performances)
- Accounts, show history & gugak temperature persistence
- Ticket-purchase partnerships (Klook/Trazy affiliate) and cultural-center tie-ins

*Show and program data verified July 2026 — always check the booking page for final schedules.*
