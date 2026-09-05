# The Rolling Root

Single-page site for The Rolling Root — tropical plant service and container gardens
for Main Street, downtown Cartersville, Georgia.

## Contents

- `index.html` — the whole site
- `support.js` — rendering runtime (must sit next to index.html)
- `assets/` — photography and brand imagery

## Running it

It is a static site. No build step, no dependencies.

Locally:

    npx serve .

Deploying: point any static host at this folder.
On Vercel, "Add New → Project", import this repo, and accept the defaults
(Framework preset: Other, no build command, output directory `.`).

## What's wired up

- Shopping cart with pickup or local delivery, persisted to localStorage
- Order and quote forms hand off to email (`therollingroot@gmail.com`)
- Text-to-order link to (470) 888-0373
- LocalBusiness structured data for local search

## Still to do

- Service prices in the four service cards are placeholders — replace with real numbers
- Checkout is an email handoff; swap in a Square payment link to take money directly
- 8 of 9 shop items have no photograph yet and use a botanical monogram placeholder
