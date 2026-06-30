# P|PW — "ChatGPT version" review build

Isolated refinement of the current site. The original files in `Downloads/` are untouched; everything here is in `Downloads/chatgpt-version/`.

The amber **⚑ INTERNAL REVIEW** strip and inline flags are internal-only — delete them before any sponsor-facing/production deploy (search `review-strip` / `review-flag`).

---

## ⚑ Asset gaps — what would lift this to truly premium

1. **Sponsor logos — resolution/format is the #1 limiter.**
   NVIDIA & Dell are clean SVG. Everything else is low-res raster pulled from the live WP site (~300px webp/png). On a white wall at large sizes they soften.
   → **Supply vector (SVG) or hi-res PNG** for: Adobe, Maxon, Blackmagic, Intel, AMD, Atomos, Fujifilm, HP, AJA, ASUS, UGREEN, Wasabi, Promise, Wacom, Antigravity, SMG, GalsNGear, ProductionHUB, The Making Of, Ripple.

2. **Conference / training photography is missing.**
   The only event photos on the site are the **networking party** and **field-workshop** collages. There is **no classroom/training-session, session-floor, or crowd/environment photography.**
   → Supply broader conference imagery — it would strengthen the homepage AI + audience sections and every edition page.

3. **Speaker photography.**
   The AI section and (eventually) the NY program read as decorative without faces.
   → Supply **speaker headshots** (and confirm which speakers can be shown — see open question).

4. **Location-specific event photography.**
   Inner pages currently use only the skyline banner + shared networking/field images, so they feel templated.
   → Per-market **on-site photos** (Vegas/NY/London/Mumbai) would make each edition feel curated.

5. **Sponsor booth / demo-table photography.**
   The sponsorship page sells "demo tables" and on-floor presence with no supporting imagery.
   → Supply **booth/activation photos**.

6. **Homepage hero source.**
   Current `hero.jpg` is 1920×1080 — fine, slightly soft on large 4K displays. A 2560px export would be crisper. Inner skyline banners are 2560px (good).

## ❓ Open questions

- **NY program speakers:** Elise asked not to publish speakers until confirmed. The grid currently shows illustrative names. Keep illustrative, blur, or hold the grid until confirmed?
- **Sponsor proof:** Any real **sponsor testimonials/quotes** or logos-with-results we can add to the sponsorship page for commercial credibility?
- **Costs:** Confirmed staying off the site (teaser → proposal). The sponsorship page reflects that.

---

## What changed in this build
- Removed all prototype/draft/sample/placeholder language across all 6 pages (banners, titles, footers, NY dev UI).
- Removed the NY "Preview mobile" dev control and draft hint box.
- **Inner pages (NY, Vegas, London, Mumbai):** skyline is now a **clean atmospheric banner** that fades into the page background; the label, headline, copy, date/venue, and CTAs moved into a calm editorial block **below** the image (no more text over the skyline).
- **Hero sponsor logos** optically normalized by perceived weight (Adobe ↑, Dell ↑, Blackmagic reined in, Intel protected, NVIDIA/Maxon as anchors).
- Added internal review strip + inline asset flags.

## Intentionally preserved (already working)
- Narrative/section order, the four-edition system, sponsorship logic, skyline-image system, partner roster & tiers, copy (only prototype language touched).
- Homepage hero keeps content over the skyline (the brief's "content off image" correction was for inner pages only).
