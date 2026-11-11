# Arifin Son — about page

Personal "about me" page for Arifin Son ("Fiin") — a student in Samarinda who
builds things on the side. Rebuilt from scratch as a single static site,
styled as a student logbook / ID card: ruled-paper background, an ID-card
hero, a school report card, an education timeline, and a sticker-style
toolbox of the languages and platforms used.

## What's new in this version

- Full visual rebuild (new layout, type system and color palette) — not an
  edit of the previous version.
- Education timeline: SDN 011 Samarinda Utara → MTs An-Nur Samarinda → SMA
  (not decided yet), with the real MTs An-Nur crest.
- A "report card" of favourite subjects: ICT, Mathematics, Science, Social
  Studies and English.
- A toolbox section split into "Languages & frameworks" (unchanged) and
  "Platforms & tools" — the newly added skills: Vercel, Supabase, Convex,
  AWS, Polar and Roblox Studio.
- A fallback avatar (shown until a real photo is added) instead of a broken
  image, the same idea as a default profile picture on a messaging app.
- A language switch (English by default, Bahasa Indonesia as an option) —
  every piece of text on the page has both, toggled with no page reload.
- Fully responsive, down to small phones, with a mobile menu, visible
  keyboard focus and `prefers-reduced-motion` support.
- A loading screen on first visit that stays up until every image on the
  page (photo, school crest, company logos, language/platform icons) has
  actually finished loading — so nothing ever appears half-loaded — with a
  6-second safety timeout in case an asset stalls.
- Extra responsive/touch polish: larger tap targets on phones, safe-area
  padding for notched devices, and tuned layout down to 320px-wide screens.

## Structure

- `index.html` — the whole page (single file, no build step, no external
  JS framework)
- `assets/logos/` — Telosion Inc., NexBlox and MTs An-Nur Samarinda logos
- `assets/icons/` — language/framework and platform icons used in the
  toolbox

Open `index.html` directly in a browser, or deploy the folder as-is to any
static host (GitHub Pages, Vercel, Netlify, etc.).
