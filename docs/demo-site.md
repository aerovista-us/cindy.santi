# Cindy Santi — Demo Site & Sales Presentation

## Sales Presentation Package
- **index.html** — Customer-facing presentation with download links for all assets (demo site, logos, flyers, documents)
- **README.md** — GitHub repo overview and quick start
- **.gitignore** — Standard exclusions for GitHub upload
- See README for GitHub Pages deployment.

---

## Demo Site Overview
Single-page responsive demo site showcasing Cindy Santi's coaching offerings, built from the intake form and proposal details.

## Pages & Sections
- **Hero** — Brand, tagline, core message, CTAs (View Offerings, Start with Intake, Book a Consultation)
- **About** — Human development focus, delivery modes (Zoom, in-person Idaho, retreats), differentiator (70 years of experience, tools for liberation)
- **Services** — One-on-one coaching, retreats, talks & workshops; delivery modes
- **Pricing** — Loaded from `pricing_products.json`: consultation, single session, 1/3/6-month packages
- **How It Works** — 4-step process: consultation → intake → choose path → transform
- **Client Intake Form** — Name, email, phone, timezone, interest, package preference, notes
- **Footer** — Contact, email, service areas

## Brand
- Colors: `#2b8c7a` (teal), `#74c6ab` (light teal), `#f2e8df` (warm cream), `#e8ddd2` (sand)
- Fonts: Crimson Pro (display), Source Sans 3 (body)
- Tone: Friendly, approachable (per intake form)

## Data Sources
- Pricing: `pricing_products.json` (fetched at load; fallback copy if unavailable)
- Content: `intake form.txt`, proposal, coaching agreement

## Intake Form Behavior
- Demo: submit shows alert; in production would POST to backend (Formspree, Netlify Forms, etc.) or email automation
- Fields: name*, email*, phone, timezone, interest*, package interest, notes

## Next Steps (Per Proposal)
- Booking integration (Calendly / Square)
- Payment checkout pages
- Email capture + automation hooks
- Connect intake to real form handler
