# RootMap Website — CLAUDE.md

## What is this?
Marketing landing page for RootMap — iOS nutrition app for Gen Z. No framework.

**Tagline:** "Root Cause, Revealed."
**Core message:** No bad food. Food is a body translator, not a calorie counter.

---

## Stack
- Plain HTML/CSS/JS — split across three files:
  - `index.html` — HTML structure only
  - `styles.css` — all styles
  - `main.js` — all JavaScript
  - `config.js` — environment config (gitignored, not committed)
- Google Fonts: EB Garamond (serif only, no sans-serif ever)
- Waitlist emails → Loops (`https://app.loops.so`)
- GitHub: `JoonEom/rootmap-landingpage`
- Hosted on Vercel: `https://www.getrootmap.com` (also `https://rootmap-landingpage.vercel.app`)

---

## Design System

| Role | Value |
|---|---|
| Background | `#FBF0E6` |
| Card bg | `#F0E6D3` |
| Olive accent | `#7A8C3A` |
| Primary text | `#2D1200` |
| Secondary text | `#7A5535` |
| Muted | `#B09070` |
| Terracotta | `#C4622D` |
| Amber | `#C9973A` |

Typography: EB Garamond Bold for headings, EB Garamond for body, EB Garamond Italic for taglines. Never use system fonts.

---

## Sections (in order)
1. **Nav** — sticky, blur, centered tab links for all sections (no CTA button)
2. **Hero** — headline, tagline, single "Get Early Access" CTA, two phone screenshots
3. **Problem** — old way vs RootMap contrast cards with auto-rotating carousel (5 slides)
4. **How It Works** — 4 steps: Personalize → Describe → Translate → Optimize
5. **Six Zones** — Glow · Build · Focus · Energy · Gut · Restore (full outcome pills per zone)
6. **Made For You** — personalization section: outcome customization copy + two phone screenshots
7. **App Preview** — dark section, feature list, phone screenshot
8. **Mission** — centered copy block
9. **Waitlist** — Loops email capture form with loading/success/error states
10. **Footer**

---

## Nav
- 3-column grid layout: logo left, tabs centered, empty right column for balance
- Tabs link to: Problem, How It Works, Six Zones, The App, Mission, Waitlist
- Scrolled state: frosted glass background + subtle shadow

---

## Images
All real images are in `pictures/`. Filenames:
- `transparent-logo.svg` — nav + footer logo
- `mvpview.png`, `foodview2.png` — hero phone screenshots
- `personalize.PNG`, `scanview.png`, `foodview.png`, `cardview.png` — How It Works step images (steps 1–4)
- `customize1.jpg`, `customize2.PNG` — Made For You section phone screenshots
- `homeview.png` — App Preview section

---

## Rules
- No calorie language, no shame framing — ever
- EB Garamond serif only
- Mobile responsive (stack at 768px)
- Waitlist: Loops embed form, handles rate limiting, loading, success, and error states

---

*Last updated: April 10, 2026*
