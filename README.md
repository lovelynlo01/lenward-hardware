# Lenward Hardware Trading

A single-page website for **Lenward Hardware Trading**, a family-run hardware store in Kota Kinabalu, Sabah, serving customers since 1994.

🔗 **Live site:** https://yourusername.github.io/lenward-hardware/

## About

Lenward Hardware Trading stocks paint, tools, plumbing, electrical, and general hardware supplies. This site lets customers browse the catalog, estimate paint quantities, and order directly via WhatsApp — with fitting, color matching, and final viewing still handled in-store.

## Features

- **Product catalog** — filterable by category (paint, tools, plumbing, electrical, hardware)
- **Paint calculator** — estimates litres and cans needed based on wall size, coats, and surface type
- **WhatsApp ordering** — tapping "Order" opens WhatsApp with the product and size pre-filled, routed to one of two contacts
- **Responsive design** — mobile-friendly layout with a sticky order bar on small screens
- **Store info** — opening hours, address, and contact details

## Tech stack

- Plain HTML, CSS, and vanilla JavaScript (no build step, no dependencies)
- Google Fonts (Oswald, Inter, JetBrains Mono)
- Tabler Icons (via CDN)

## Project structure

```
.
└── index.html   # entire site — markup, styles, and scripts in one file
```

## Running locally

No build tools needed. Just open `index.html` in a browser, or serve it locally:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deployment

Hosted via **GitHub Pages**.

1. Push changes to the `main` branch
2. GitHub Pages auto-deploys from the repo's configured branch/folder (Settings → Pages)
3. Changes typically go live within a minute or two

## Configuration

WhatsApp numbers are set near the top of the `<script>` block in `index.html`:

```js
const WA_DAD = "60128101168";
const WA_BRO = "60128983368";
```

Product listings (name, category, size, price, icon) are defined in the `products` array in the same file.

## Contact

- **Address:** Lot 2, Blok P, Batu 3, Jalan Penampang, Taman Che Mei, 88200 Kota Kinabalu, Sabah
- **Hours:** Mon–Sat, 10:30am – 5:00pm (closed Sundays & public holidays)
- **Phone:** 088-249 123

---

© 2026 Lenward Hardware Trading. All prices subject to change in-store.
