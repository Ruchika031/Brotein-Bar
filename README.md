# Brotein Bar

Online ordering and menu website for **Brotein Bar**, a campus food startup at LM Thapar School of Management serving fresh, protein-rich vegetarian Indian meals in the evening (4:00 PM to 8:00 PM).

**Founders:** Bhawna and Ruchika | **Contact:** 9729505574

| | |
|---|---|
| Live ordering app (Lovable) | https://brotein-bar-orders.lovable.app/ |
| Brand website (Manus) | https://broteinbar-suur89zt.manus.space/ |

## Problem
Customers had to call repeatedly to place or repeat an order, which was slow for customers and hard to manage during a four-hour evening service window.

## Solution
A mobile-friendly menu and ordering experience that lets customers browse the menu, see nutrition information and order without calling, plus a brand website covering the offering, hours and founders.

## Results
- 500 orders handled in one month (evening-only service)
- ~₹250 average order value
- Operations and finances managed end to end by the founders

## Features
- Menu of 15+ items across salads, sandwiches, snacks, drinks and bars
- Approximate nutrition per serving (calories, protein, carbohydrates, fat, fibre) on each item
- Repeat ordering without phone calls
- Service hours, founders and contact details on the site
- Mobile-first layout

## Tech stack
React, Express, tRPC, Drizzle ORM, pnpm, Docker. The ordering app was built with Lovable and the brand website with Manus.

## Run locally
```bash
pnpm install
pnpm dev        # development server on port 3000
pnpm build      # production build
pnpm start      # serve dist/index.js
pnpm check      # type checks
pnpm test       # tests
```
Do not commit `.env` files or API keys.

## Notes
- Nutrition values are estimates based on standard ingredients and typical portions, not lab-tested.
- Packaged items (for example Yoga Bar) follow the manufacturer's label.
- Promo video: `media/brotein-bar-promo.mp4` (AI-generated visuals; illustrative, not a screen recording).

## Documentation
Product overview and user stories: [PRODUCT_OVERVIEW.md](PRODUCT_OVERVIEW.md). Setup notes: [SETUP.md](SETUP.md).

## Author
Ruchika Goyal, MBA (Business Analytics & Marketing), LM Thapar School of Management
