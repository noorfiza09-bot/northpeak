# NorthPeak Digital — one-page agency site

Fictional Shopify dev agency site built for the Digital Heroes Web Development task (Role 05, Task A).

## What's here
- `index.html` — single self-contained file (HTML + CSS + JS, no build step, no dependencies besides Google Fonts CDN).

## Design notes
- **Concept:** the name "NorthPeak" is taken literally — the whole visual identity is built around ascent (an elevation-line motif in the hero and as section dividers, pricing tiers named Basecamp / Ascent / Summit).
- **Palette:** near-black ink base with an "alpenglow" amber-to-magenta gradient accent, chosen to avoid the generic cream/serif and near-black/single-accent looks AI tools default to.
- **Type:** Space Grotesk (display), Inter (body), JetBrains Mono (stats and pricing digits).
- Tested visually at 360px, 768px, and 1440px breakpoints. Respects `prefers-reduced-motion`. Focus states are visible on all interactive elements.

## Deploy it yourself (2 minutes, no account needed for Netlify Drop)

**Option A — Netlify Drop (fastest):**
1. Go to https://app.netlify.com/drop
2. Drag the `index.html` file (or the whole folder) onto the page.
3. Netlify gives you a live URL immediately — that's your live link for submission.

**Option B — Vercel or GitHub Pages**, if you'd rather have it under your own account/domain — both also just need the single HTML file pushed to a repo.

## Push to a public GitHub repo
```bash
cd northpeak
git init
git add index.html README.md
git commit -m "NorthPeak Digital — one-page agency site"
git branch -M main
git remote add origin https://github.com/<your-username>/northpeak-digital.git
git push -u origin main
```
Make sure the repo is set to **Public** before you submit the link.

## Before you submit
- [ ] Live URL loads correctly in an incognito window
- [ ] Repo is public
- [ ] Footer credit line ("Built for Digital Heroes Training Task") is visible and links to digitalheroesco.com — already included
- [ ] AI-use paragraph written for your submission (see suggestion below)

### Suggested AI-use paragraph (edit to be true to what you actually did)
> I used Claude to scaffold the HTML/CSS/JS structure and generate the ascent-line SVG motif, then rewrote the hero headline, service descriptions, and pricing framing myself to match a voice I wanted, adjusted the color pairing after testing a few options, and fixed [X] on my own after testing on mobile.
