# 🌍 ecoKart — Shop with your carbon in mind

A carbon-aware shopping platform that shows the CO₂ footprint of every product, helping people make informed, planet-friendly purchasing decisions.

**Live demo:** _Deploy to GitHub Pages — see instructions below_

---

## What it does

ecoKart is a single-page shopping platform where every product displays its **carbon footprint in kg CO₂ equivalent (CO₂e)** alongside its price. Shoppers can:

- Filter products by carbon level (low / medium / high)
- Sort by carbon footprint to find the greenest option
- See a real-world equivalent for each product's CO₂e (e.g. "≈ driving 22 km")
- Track their cart's total carbon cost vs. the daily sustainable budget (5.5 kg CO₂e)
- Get a warning when their cart exceeds the sustainable daily limit

---

## How to deploy (GitHub Pages — free)

1. Fork or upload this repo to your GitHub account
2. Go to **Settings → Pages**
3. Under "Source", select **main branch** and **/ (root)**
4. Click Save — your site will be live at `https://yourusername.github.io/ecokart`

That's it. No server, no build step, no dependencies.

---

## File structure

```
ecokart/
└── index.html    ← entire app, self-contained
```

---

## Tech stack

- Pure HTML, CSS, JavaScript — no frameworks, no dependencies
- Zero build step — works directly in the browser
- Fully responsive

---

## Carbon data sources

- IPCC AR6 Working Group III (2022) — ipcc.ch
- BBC Science Focus — sciencefocus.com
- Our World in Data — ourworldindata.org
- WWF Carbon Footprint Calculator — footprint.wwf.org.uk
- Carbon Trust Product Footprint Database — carbontrust.com
- UNEP Emissions Gap Report 2023 — unep.org

---

## Extending the product list

In `index.html`, find the `PRODUCTS` array and add entries in this format:

```js
{ id: 13, name: "Greek yoghurt", brand: "Epigamia 200g", emoji: "🫙", price: 75, co2: 0.45, category: "dairy", rating: 4.3, reviews: 890 }
```

Categories: `snacks` | `personal` | `clothing` | `dairy` | `electronics`

---

_Built for the Climate Change Exhibition — April 1, 2026_
