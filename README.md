# HMD Shop SEO mockups

HTML mockups showing how the HMD Shop pages can be redesigned for SEO, while keeping the live shop's look and feel. Prepared by RunCommerce.

## Pages

| Page | File | What it shows |
|---|---|---|
| Homepage (UK) | [index.html](index.html) | H1 and intro, shop by category, colourful product cards with swatches, delivery and returns, SEO text block, FAQ |
| Smartphones category (UK) | [smartphones.html](smartphones.html) | Breadcrumb, intro, "shop by type" links, product grid, comparison table, buying guide, FAQ |
| HMD Fusion X1 product page (UK) | [hmd-fusion-x1.html](hmd-fusion-x1.html) | Full product content, features, specs, FAQ, all as compact dropdowns |
| HMD Fusion X1 product page (Ireland) | [hmd-fusion-x1-ie.html](hmd-fusion-x1-ie.html) | Final Ireland content in euro: buy box, spec chips, benefit blocks, specs, FAQ, EU energy label |

The pages link to each other: homepage to category to product, and back through the breadcrumbs and header. Links to anything not mocked up go to the live shop.

## How to view

Open `index.html` in any browser, or download the repo as a ZIP and open the files locally. An internet connection is needed, because product images load from gb.shop.hmd.com and ie.shop.hmd.com, and the font loads from Google Fonts.

## Notes for reviewers

- Text marked *lorem ipsum* on the homepage and category page is placeholder copy, showing where SEO content goes.
- Images tagged **Dummy image**, **Dummy colours** or **Dummy product** are placeholders for real photography or product data.
- Yellow **CONFIRM** tags on the Ireland page mark facts that HMD still needs to confirm (Android version, security updates, warranty, Xplora euro price, EU label values).
- Each page carries its own structured data (Product, BreadcrumbList, ItemList, FAQPage) in the page head. Canonical tags point to the live shop URLs the page is intended for.
