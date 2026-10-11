# lavella-media: image host for the Lavella console

Updated 2026-10-11.

This repository has one job: to serve the images used by the Lavella console on the Shopify store (mylavella.com). GitHub Pages publishes them at:

`https://aj-insight-dev.github.io/lavella-media/<file name>`

The console itself is a single Shopify theme section built from `lavella-site` (run `node scripts/build.mjs`, then paste `dist/sections/lavella-console.liquid`). Nothing in this repo runs on the site except these images.

**This repo is public.** Only images and this README belong here: no customer details, costs, margins, passwords or keys.

**Publishing:** Settings → Pages → Build and deployment → Source: **Deploy from a branch** → `main` / `/ (root)`. Every image sits at the repo root. No folders, and no workflow file.

## What changed in this update
- First upload. The repo was created for the console.
- 53 images. They are product photos from the store, and brand, care and seasonal photos. All are JPEG at about 85% quality, at most 1600 px. The logo and icons are PNG.
- The seasonal photos (`season-*.jpg`) and the "Unlock a world" images (`unlock-*.jpg`) are cropped from Amy's own photo files. Any screenshot text was left out.

## Every file in the repo
| File | Size |
|---|---|
| `brand-1.jpg` | 88 KB |
| `brand-2.jpg` | 85 KB |
| `brand-3.jpg` | 88 KB |
| `cotm-halloween.jpg` | 54 KB |
| `family.jpg` | 183 KB |
| `icon-handmade.png` | 42 KB |
| `icon-ifra.png` | 10 KB |
| `icon-owned.png` | 29 KB |
| `logo-wing-l.png` | 6 KB |
| `logo-wing-r.png` | 6 KB |
| `logo-word.png` | 5 KB |
| `logo.png` | 19 KB |
| `p-aurora.jpg` | 222 KB |
| `p-autumn-cider.jpg` | 32 KB |
| `p-bliss.jpg` | 189 KB |
| `p-cafe.jpg` | 248 KB |
| `p-cashmere.jpg` | 145 KB |
| `p-castaway.jpg` | 212 KB |
| `p-cinnamon-harvest.jpg` | 30 KB |
| `p-coastal.jpg` | 212 KB |
| `p-crystal.jpg` | 180 KB |
| `p-delicate.jpg` | 121 KB |
| `p-elevated.jpg` | 196 KB |
| `p-fleurs.jpg` | 182 KB |
| `p-flora.jpg` | 305 KB |
| `p-havana.jpg` | 213 KB |
| `p-myduology.jpg` | 169 KB |
| `p-naked.jpg` | 194 KB |
| `p-oasis.jpg` | 200 KB |
| `p-parchment.jpg` | 156 KB |
| `p-petrichor.jpg` | 192 KB |
| `p-polynesia.jpg` | 226 KB |
| `p-pumpkin-butter.jpg` | 28 KB |
| `p-pumpkin-hollow.jpg` | 34 KB |
| `p-quartz.jpg` | 152 KB |
| `p-shipwreck.jpg` | 195 KB |
| `p-speakeasy.jpg` | 222 KB |
| `p-subscription.jpg` | 122 KB |
| `p-tempest.jpg` | 227 KB |
| `p-topaz.jpg` | 147 KB |
| `p-vintage.jpg` | 208 KB |
| `p-woodland.jpg` | 283 KB |
| `season-autumn.jpg` | 199 KB |
| `season-halloween.jpg` | 132 KB |
| `season-pumpkin-hollow.jpg` | 119 KB |
| `tip-extinguish.png` | 12 KB |
| `tip-leave.png` | 16 KB |
| `tip-placement.png` | 6 KB |
| `tip-time.png` | 9 KB |
| `tip-trim.png` | 9 KB |
| `tip-water.png` | 9 KB |
| `unlock-grid.jpg` | 109 KB |
| `unlock-lineup.jpg` | 65 KB |
| `README.md` | this file |

## Notes
- To change a photo, upload a new file with the **same name**. No code change is needed.
- To add a new candle, put its photo here and add it to `lavella-site/src/products.mjs`. Then rebuild and re-paste the section.
