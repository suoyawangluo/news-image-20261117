# Sources — news of Tuesday 17 November 2026

All six stories were reported on 17 November 2026 (any time zone). Facts are
as reported; nothing is invented. The image itself is original work: a
front page drawn from scratch (HTML + inline SVG, screenshotted locally).

1. **Ukraine strikes Crimean Bridge again; Kyiv bridges hit** (lead)
   - Ukraine struck the Kerch/Crimean Bridge for a second consecutive day;
     traffic suspended (Moscow-installed Crimea head Sergei Aksyonov, via
     Al Jazeera; Outlook India; The War Zone).
   - President Zelenskyy hailed an "unprecedented operation" (Just Security,
     Early Edition, 17 Nov 2026).
   - Russian ballistic missiles struck Kyiv's Northern and Southern bridges
     over the Dnipro, disrupting water, heating and power (Kyiv mayor Vitali
     Klitschko, via BBC, carried by WhatTech world-news roundup, 17 Nov 2026).

2. **Tankers hit mines off Hormuz**
   - Iran's Revolutionary Guard navy said two oil tankers struck mines and
     caught fire on a route south of the Strait of Hormuz; Iran's regular
     navy said further tankers were hit east of the strait (Al Jazeera;
     Reuters via Arab News; Algenom news roundup, 17 Nov 2026).
   - USS Theodore Roosevelt arrived, giving the US three aircraft carriers in
     the region (CNBC; One Turn world-news roundup, 17 Nov 2026).

3. **Trump joins Quad in Manila**
   - Trump arrived in Manila on Tuesday for the Quad leaders' meeting on the
     ASEAN summit sidelines (Outlook India live blog, 17 Nov 2026).
   - China confirmed the first Xi–Trump–Putin three-way meeting, set for
     Thursday 19 November in Shenzhen on the APEC sidelines (China foreign
     ministry, via Outlook India).
   - US–Thailand reciprocal trade agreement reached "substantial conclusion",
     joint statement issued in Manila on 17 November (White House, via
     IntraAlpha Morning Market Briefing, 17 Nov 2026).

4. **U.S. loses measles-free status**
   - PAHO announced on Tuesday that endemic measles transmission has been
     re-established in the United States, Mexico and Bolivia; the US held
     elimination status since 2000 (PAHO news release, 17 Nov 2026; Al
     Jazeera; Reuters via Daily Maverick).
   - 5,412 confirmed US measles cases in 2026 as of 12 November, the highest
     total in 35 years (CDC figures, via Healthline/Healio).

5. **Nvidia booms; no Huang return**
   - Nvidia reported fiscal Q3 revenue of $115.8bn, up 103% year on year,
     beating estimates, and guided Q4 revenue to ~$130bn (The National News;
     Chosun Biz; Converge Digest, 17 Nov 2026).
   - Jensen Huang said on Tuesday he would be honoured to return as CEO if
     the board asked; board chair Harvey Jones said on the earnings call the
     board "does not intend to reinstate Jensen as CEO"; Colette Kress is
     interim CEO (TMJ4; NBC Palm Springs; LinkedIn News, 17 Nov 2026).

6. **Serbia's students take parliament**
   - Serbia's Student List deputies were sworn in on Tuesday in the first
     parliamentary sitting since the 25 October election, winning 140 of 250
     seats and ending 14 years of rule by Aleksandar Vučić's Serbian
     Progressive Party (Reuters via WNCY, 17 Nov 2026; AFP via NZ Herald /
     Daily Sabah / Kuwait Times, 17 Nov 2026).

## Build

- `design.html` — the front-page design (original HTML/CSS + hand-drawn
  inline SVG illustrations; no photos, no copied artwork).
- Rendered locally with headless Chromium (no network) at exactly
  1024×1024: `chrome-headless-shell --headless --screenshot=entry.png
  --window-size=1024,1024 design.html`.
- `main.ts` copies the committed `entry.png` to
  `$MAKEFUN_OUTPUT_DIR/entry.png` (Node standard library only, no network).
