# Musholm — Discover Seafood page

Corrected copy of https://discoverseafood.world/musholm (saved Squarespace page).
The live site is unchanged until the same edits are made in the Squarespace editor.

## Files

- `index.html` — preview for GitHub Pages. Same content as the saved page, with images loaded from
  the Squarespace CDN and the site stylesheet copied into `assets/`. Squarespace's own scripts are
  removed; a small script keeps the accordions working, and the Google Map is replaced by a link.
- `musholm-discover-seafood.html` — the corrected browser save. To view it locally, place it next to
  the original `Musholm — Discover Seafood_files` folder.

## Changes

1. **Share image** — `og:image` pointed to Kvarøy Fiskeoppdrett's image; now the Musholm sea-farm photo.
   In Squarespace: Page Settings → Social Image.
2. **SEO / share description** — replaced "Discover Seafood tracebility tool" with:
   "Meet Musholm, Danish trout farmers raising fish from spring water to sea. ASC-certified, the first
   aquaculture company with Science Based Targets for Nature, fed with BioMar Blue Impact."
3. **Nature target numbering** — first target was a one-item auto-numbered list; now "1. Reducing pressure
   on wild fish stocks", matching "2." and "3.".
4. **Nutrition** — percentages recalculated against EU Reference Intakes (Regulation (EU) 1169/2011, Annex XIII);
   "filet" → "fillet"; states raw fillet (to be confirmed with Musholm); sodium shown as salt (0.1 g);
   EPA+DHA, omega-3, omega-6 and cholesterol shown as "–" (no reference intake).

   | Nutrient | Amount | % RI |
   |---|---|---|
   | Energy | 149 kcal / 623 kJ | 7.5% |
   | Protein | 20.8 g | 41.6% |
   | Fat | 7.2 g | 10.3% |
   | Saturated fat | 1.0 g | 5.0% |
   | Carbohydrates | 0 g | 0% |
   | Salt | 0.1 g | 1.7% |
   | Vitamin D | 4.94 µg | 98.8% |
   | Vitamin B6 | 0.21 mg | 15.0% |
   | Vitamin B12 | 2.49 µg | 99.6% |
   | Calcium | 18 mg | 2.3% |
   | Iron | 0.29 mg | 2.1% |
   | Magnesium | 26 mg | 6.9% |
   | Phosphorus | 210 mg | 30.0% |
   | EPA + DHA | 0.75 g | – |
   | Omega-3 | 1.4 g | – |
   | Omega-6 | 1.3 g | – |
   | Cholesterol | 46.45 mg | – |

5. **Carbon footprint unit** — "1.44 CO₂ eq. / kg feed" → "1.44 kg CO₂e / kg feed" (also in the
   screen-reader text). See `carbon-footprint-widget.png`.

## Consumer version (`consumer/index.html`)

A rewrite for shoppers who scan the QR code in store, built in the existing Discover Seafood style
(same palette, Montserrat type, grey cards, navy sections, icon menu, accordions and the three impact
gauges). Same facts as the current page, reordered and in plain language: the trout's journey,
nutrition highlights (full table folded away), ASC, the three nature targets, the feed, two simple
recipes, and contact. The map is an OpenStreetMap embed, as Google's embed needs an API key.

To confirm with Musholm before use:
- The three sea farms are in the Great Belt (the page says so).
- Trout species (for example rainbow trout), and whether roe should be mentioned.
- Nutrition figures are for raw fillet.
- Nutrition wording ("high in protein, omega-3, vitamin D and vitamin B12") meets EU nutrition claim
  rules (Regulation (EC) 1924/2006), and environmental wording is reviewed against EU green claims rules.
- The ASC logo is shown, as on the current page; check Musholm's ASC logo licence covers consumer use.
- The contact email (currently Teis Volstrup's direct address).

## Concept version (`concept/index.html`)

A free-design take on the consumer page, not bound to the current Squarespace template. Editorial
layout with Source Serif headlines and Montserrat body; answers "where is it from?" in the first
screen; every number is visible without hovering; the nature targets become three big figures
(56 ha, ½, 2 seas); the feed gauges become simple scales marked "higher/lower is better"; and a
"your pack" placeholder shows where batch-level traceability (farm, harvest date) would go.
Same facts as the other versions, and the same points to confirm apply.
