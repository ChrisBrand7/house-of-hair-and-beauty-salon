# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS/JS (no framework, no build step) — existing, confirmed by repo (`index.html`, `style.css`, `script.js`).

## Users

Primary users are local residents of Paradyskloof / Stellenbosch researching and booking hair and beauty services, then booking via WhatsApp.

## Product Purpose

A single-page marketing/booking site for House of Hair & Beauty, a real, operating salon in Paradyskloof, Stellenbosch. It exists to showcase the salon's interior, team, and services, build trust via real Google reviews, and convert visitors into WhatsApp bookings.

## Positioning

A family-run salon: owner Liana Nel and her daughter Carla Nel run the floor together. Real reviews repeatedly praise specific named stylists (Hanli Langer, Clarece, Elize, Janine, Stephanie, Stefani) and long-standing customer loyalty — this personal, long-tenure feel should stay the throughline in future copy.

## Operating Context

- Address: 37 Canterbury Ln, Paradyskloof, Stellenbosch, 7600 (confirmed via the business's real Google Maps listing).
- Hours: Mon–Fri 8:00am–5:00pm, Saturday 8:00am–1:00pm, Sunday closed (confirmed via Google Maps listing).
- Published landline: 021 880 1729 (real, shown on the storefront signage and Google Maps listing) — used for `tel:` links.
- WhatsApp booking number: `https://wa.me/27609820397` (+27 60 982 0397) — supplied directly by the client as a temporary number; the salon does not yet have its own dedicated WhatsApp number.
- Rating shown: 4.6 on Google, 98 reviews (real, from the business's Google Maps listing).

## Capabilities and Constraints

- All Google reviews displayed must be real, verbatim (or lightly trimmed) quotes from actual reviewers with their real names — currently 5 reviews selected from a larger real batch supplied by the client (Hayley Basson, Faieza Paloan, Corli Bosman, Gerhard Olivier, Marcelle du Plessis), filtered to recent (within ~1 year) and positive.
- Gallery photos are real photos of the actual salon and team, supplied by the client (`images/hero-image.jpg`, `images/customer-care.jpg`, `images/two-generations.jpg`, `images/treat-yourself.jpg`, plus unused-for-now `our-team-1.jpg`, `our-team-2.jpg`, `laugh-with-us.jpg`, `product-range.jpg`, `storefront.jpg`).
- **Open / not yet real — do not treat as launch-ready:**
  - **Full price list** (`services.html` and the category list in `index.html#services`) still shows the previous client's (K3 Hair & Beauty Salon's) real pricing and service categories (Threading, Waxing, Facials, Nails, Hair, Make-up, Massage, Mehndi). This has NOT been confirmed for House of Hair & Beauty and must be replaced with real services/pricing before launch. Flagged with `TODO` HTML comments in both files.
  - **TikTok** removed entirely — the salon doesn't have an account. Instagram (`houseofhair_stb`) and Facebook are real and live.
  - **Business email** — not yet supplied; privacy-policy.html and terms.html currently route contact via phone/WhatsApp only.
  - **WhatsApp number** is a temporary personal number provided by the client, not the salon's own — replace once the salon has one.

## Brand Commitments

- Name: House of Hair & Beauty (Google Business listing: "House Of Hair And Beauty"; storefront signage reads "House of Hair").
- Visual identity carried over from the previous build (not yet reviewed against this brand): cream/black/gold palette, Prata display type paired with Manrope body (Pairing B — High Contrast Fashion).

## Evidence on Hand

- Real Google Maps listing: name, address, hours, phone, 4.6★ (98 reviews).
- Real, recent Google reviews (full batch supplied by client; 5 selected for the site).
- Real photos of the salon interior, team, and owners (Liana & Carla Nel) in `images/`.
- No real pricing, social handles, or business email supplied yet — do not fabricate.

## Product Principles

1. Every claim on the page (review, hours, location, photo) must be real and verifiable — this is a real local business, not a template.
2. Do not reuse the previous client's (K3) real business data — address, phone, reviews, or pricing — under this business's name.
3. WhatsApp is the single, unambiguous path to action — every section should make booking one tap away.
4. Preserve the boutique/editorial visual identity (cream/black/gold, serif+sans pairing) when adding new content.
