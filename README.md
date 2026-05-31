# RSS Scraper — Material You 3 Expressive

A fully functional Progressive Web App that turns any website into a well-formatted RSS feed. Designed with Material You 3 Expressive styling — bold typography, oversized form fields, and dynamic teal color theming.

**[→ Open the app](https://indar-beurre.github.io/rss-reader-m3-pwa/)**

---

## Features

- **Smart feed discovery** — paste any URL and it auto-detects RSS/Atom feeds, or scrapes the page HTML when no feed exists
- **CSS selector scraping** — target specific page elements for sites with non-standard layouts
- **AI-powered formatting** — connect your OpenAI API key to summarize or simplify articles with GPT-4o-mini
- **Offline-first** — service worker caches the app shell; works without internet after first load
- **IndexedDB storage** — all feeds and articles stored locally on your device
- **OPML import/export** — move your subscriptions to/from any other reader
- **Auto-refresh** — configurable background refresh intervals (15 min to 24 hours)
- **18 curated sources** — one-tap subscribe to The Verge, Ars Technica, Hacker News, TechCrunch, BBC, Nature, and more

## Install on your phone

1. Open **https://indar-beurre.github.io/rss-reader-m3-pwa/** in Chrome on Android
2. Tap ⋮ → **"Install app"** (or accept the install banner)
3. Done — it runs as a standalone app, no app store needed

## AI formatting (optional)

1. Go to **Settings** inside the app
2. Paste your **OpenAI API key**
3. Articles now show "Summarize" and "Simplify" buttons powered by `gpt-4o-mini`

Costs fractions of a cent per article.

## Design

- Material You 3 Expressive — dynamic color with teal seed `#006B5E`
- Oversized form inputs (24px+ padding, 18px font, 3px borders)
- M3 shape scale (small 8px → full 9999px)
- Proper M3 color roles: surface, surface-container, primary, secondary, tertiary
- Android-native feel: status bar, navigation bar, 44px+ hit targets

## Tech

Single-file PWA (`index.html`) + service worker + web manifest. No build step, no dependencies, no framework. Just open and use.

## License

MIT
