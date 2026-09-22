# AI Automation Box — updated product page

Replacement content for https://myrepublic.net/sg/business/ai-automation-box/,
rebuilt from the "AI Automation Box GX10 Starhub v2" deck.

`index.html` is the deliverable: a complete standalone HTML document
(doctype, head, body) that opens directly in a browser and serves as-is from
GitHub Pages or any static host.

## Before deploying

The logo and the GX10 product shot are embedded as base64 `data:` URIs, because the
preview platform blocks external images. **Swap both for normal CMS asset paths** —
`logo.png` and `gx10.png` in this folder are the source files. That drops the HTML from
~288KB to ~45KB and lets the images cache separately.

## Content changes vs the live page

Replaced:
- Pricing: `$278/$388 per unit/mth, 36-month contract` -> `S$16,588 / S$30,988 one-time`
- Positioning: SME plug-and-play -> on-premise, inside your own network, air-gap optional
- Use cases and capabilities replaced with the deck's current six of each

Removed as no longer supported by the deck:
- "30+ Automation templates", "Pre-installed with recommended tool: n8n"
- "Open Source LLM of your choice", "Get my Free Trial"

Left untouched (site-wide chrome from the CMS): the scam-alert strip, the main nav,
and the "As featured in" logo strip.

## Needs sign-off before publishing

1. The customer reference ("a major Singapore enterprise") comes from a deck marked
   *Restricted. Do not distribute without permission.*
2. Optional support cover is quoted at two different prices in the deck — S$2,488/S$3,488
   standalone vs S$1,988/S$2,788 "if taken with the box". Not currently on the page.
3. Payback claim ("about a year") is stated without the competitor chart, because the deck
   has no readable competitor figures. Supply the per-seat rates if you want that chart.
