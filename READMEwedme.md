# WedMe.io

**WedMe – Cape Winelands Wedding Planning**

The latest working single-file HTML version of the WedMe wedding planning platform landing site.

## About

WedMe helps couples plan their dream wedding — starting in South Africa’s beautiful Cape Winelands (Stellenbosch, Paarl, Franschhoek) and going global.

- Elegant, romantic design with soft pastels and premium feel
- Interactive tools (especially the budget planner)
- Curated venues and vendor discovery
- Planning features for real couples

**Current status**: Latest working production-ready HTML demo (as of 28 May 2026).

## Latest Working Site

This repository contains the **latest working version**:

- Source: `wedding-hub-landing-v3.html` → `index.html`
- Fully self-contained (uses CDN for Tailwind + Font Awesome + placeholder imagery)
- Fully interactive budget planner with live ZAR calculations
- Responsive for desktop & mobile
- Modals for login / signup (demo)

**To view**:
```bash
# Simplest
open index.html   # or double-click in Finder/Explorer

# Or with a local server (recommended)
python -m http.server 8000
# then visit http://localhost:8000
```

## Key Features (from the live site)

- **Hero** with strong value prop + CTAs
- **Interactive Budget Planner** (slider + live allocated/remaining)
- **Vendor Categories** grid (Venues, Photography, Catering, Florals, Entertainment, Honeymoons…)
- **Cape Winelands Featured Venues** (Lourensford Estate, Rhebokskloof, Boschendal)
- **Trust signals** + testimonials
- **Planning Tools** section
- Sticky elegant navbar
- Footer with company links

## Tech Stack

- Pure HTML5 + Tailwind CSS (via CDN for zero-build demo)
- Font Awesome 6
- Vanilla JavaScript (budget logic, modals, smooth scroll, category selection)
- Playfair Display + Inter fonts (via Google Fonts)

No build step required.

## Related Projects

- **wedme-android-baseline** (sibling project) — Jetpack Compose Android app that mirrors the same design language, colors, and features (Budget, Wedding Board, Vendors, Vision Questionnaire). Uses Kotlin + Compose + DataStore.

## Project Structure

```
wedme.io/
├── index.html          # Latest working landing (v3)
├── wedding-hero.jpg    # Local hero / asset
├── README.md
└── .git/
```

## Future / Roadmap Notes

- Replace placeholder images (`picsum.photos`) with real high-quality wedding photography
- Extract CSS/JS into separate files for easier maintenance
- Add real backend (vendors, bookings, user accounts)
- Full onboarding flow (the signup button currently shows an alert)
- Integrate with the Android app
- Add more planning tools (guest list, timeline, seating)

## Credits & Notes

- Design aesthetic: Elegant Cape Winelands / romantic minimal
- Currency: South African Rand (ZAR)
- Original iterations were iterated in:
  - wedding-hub-landing.html
  - wedding-hub-landing-v2.html
  - wedding-hub-landing-v3.html (current latest)
  - Various backups

This repo captures the **clean, latest working state** ready for further development or deployment.

---

**WedMe** — Turning love stories into unforgettable celebrations. From the Cape Winelands to the world.

Contact: hello@wedme.co.za
