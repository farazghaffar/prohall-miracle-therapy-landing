# Prohall Miracle Therapy Kit — A/B landing pages

Static A/B landing pages for [Prohall Miracle Therapy Kit](https://shop.prohall.ai/products/brazilian-keratin-hair-treatment-kit-straightening-blowout-formaldehyde-free-prohall-professional-miracle-therapy-17oz-keratina-queratina-alisador-para-el-pelo) on shop.prohall.ai, measured with Split.

| Version | Path | Headline |
|---|---|---|
| A | `/miracle-therapy/v1/a/` | Meet Miracle Therapy — the 3-step Brazilian keratin kit |
| B | `/miracle-therapy/v1/b/` | How to use Miracle Therapy for sleek, smooth hair at home |

Both pages share `/miracle-therapy/v1/assets/styles.css`; only the `<title>` and `<h1>` differ.

## Live links (GitHub Pages)
Settings → Pages → Source: **Deploy from a branch**, branch `main`, folder `/ (root)`.

- A: https://farazghaffar.github.io/prohall-miracle-therapy-landing/miracle-therapy/v1/a/
- B: https://farazghaffar.github.io/prohall-miracle-therapy-landing/miracle-therapy/v1/b/

Keep the trailing slash.

## Deploy (Vercel, optional)
Import this repo → preset **Other**, no build command. URLs: `https://<project>.vercel.app/miracle-therapy/v1/a/` and `/b/`.

## Before starting a Split run
1. Replace the placeholder `<script ... external-landing.js>` tag at the bottom of BOTH pages with the exact tag from Split → New run → Install tracking.
2. The Shopify theme bridge (`split-tracking.js` + `split-tracking.liquid`) must be installed on the live theme.
3. Never put raw page URLs in ads — use Split's generated links.

For a redesign, add `/miracle-therapy/v2/...` and start a new run; keep v1 unchanged.
