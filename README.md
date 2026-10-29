# HMD Shop SEO mockups

HTML mockups showing how the HMD Shop pages can be redesigned for SEO, while keeping the live shop's look and feel. Prepared by RunCommerce.

## Pages

| Page | File | What it shows |
|---|---|---|
| Homepage (UK) | [index.html](index.html) | H1 and intro, shop by category, colourful product cards with swatches, delivery and returns, SEO text block, FAQ |
| Smartphones category (UK) | [smartphones.html](smartphones.html) | Breadcrumb, intro, "shop by type" links, product grid, comparison table, buying guide, FAQ |
| HMD Fusion X1 product page | [hmd-fusion-x1.html](hmd-fusion-x1.html) | Final content (Ireland, in euro): buy box, spec chips, benefit blocks, specs, FAQ, EU energy label |
| HMD Terra M product page (UK) | [hmd-terra-m.html](hmd-terra-m.html) | Final UK content in £: rugged phone buy box with add-ons, spec chips, benefit blocks, who it's for, specs, FAQ, accessories |
| Feature phones category (Ireland) | [feature-phones.html](feature-phones.html) | Breadcrumb, intro, "shop by type" links, colourful product grid of all 7 Irish feature phones, comparison table, buying guide, FAQ |
| HMD Barbie Phone product page (Ireland) | [hmd-barbie-phone.html](hmd-barbie-phone.html) | Final content in euro: buy box, spec chips, benefit blocks, who it's for, specs, compare, FAQ, EU product information |

The pages link to each other: homepage to Smartphones or Feature phones, then on to the HMD Fusion X1, HMD Terra M or HMD Barbie Phone, and back through the breadcrumbs and header. Links to anything not mocked up go to the live shop.

## How to view

Open `index.html` in any browser, or download the repo as a ZIP and open the files locally. An internet connection is needed, because product images load from gb.shop.hmd.com and ie.shop.hmd.com, and the font loads from Google Fonts.

## Notes for reviewers

- Text marked *lorem ipsum* on the homepage and category pages is placeholder copy, showing where SEO content goes.
- Images tagged **Dummy image**, **Dummy colours** or **Dummy product** are placeholders for real photography or product data.
- Yellow **CONFIRM** tags on the product pages mark facts that HMD still needs to confirm (for example warranty length, returns window, SIM and unlocked status, EU label values).
- Each page carries its own structured data (Product, BreadcrumbList, ItemList, FAQPage) in the page head. Canonical tags point to the live shop URLs the page is intended for.
