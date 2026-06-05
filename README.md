# Verdant — Shopify Theme

**A calm, biophilic botanical theme for houseplant, garden and home-botanical stores.** Verdant turns a product page into a plant-care field guide, helps shoppers find the right plant for their light and lifestyle, and wraps it all in a warm, editorial "botanical magazine" aesthetic.

**Who it's for:** indoor plant shops, nurseries, garden centers, planter/pottery brands, and any home-botanical store that wants to look like a boutique plant studio rather than a generic catalog.

---

## Key features

### Botanical / niche sections (what makes Verdant different)

- **Plant-care spec panel** — the signature section. A "care at a glance" field guide on the product page: light, water, humidity, difficulty, mature size, hardiness zone, plus a 1–3 dot difficulty meter and pet-safe / air-purifying notes. Each spec can read a **product metafield** (e.g. `custom.light`, `custom.water`) so values are driven per-product, with a sensible manual fallback so it looks great with zero setup.
- **Care finder** — a "shop by how you live" tile grid that links to filtered collections (Low-light heroes, Pet-safe picks, Beginner easy, Low-water, Statement bloomers, Desk & shelf size). This is the storefront entry point for care-based browsing.
- **Care guide** — an editorial, numbered "how to keep it thriving" walkthrough (water, light, feed, repot, prune…) in a sticky magazine layout, with an optional image and call-to-action.
- **Botanical hero** — an asymmetric editorial homepage hero where one oversized portrait plant photo is masked into an organic blob, overlapping a serif headline with small floating care chips (Light / Water / Pet-safe).
- **Lookbook** — a magazine-style "live the look" / "from our greenhouse" image mosaic with optional captions and links.
- **Product facts / details accordion** — a tidy, collapsible product-detail panel (pot size, ships-at size, plant details, care steps) for the deeper specs.
- **Care-based faceted filtering** — works with Shopify's native **Search & Discovery** app so shoppers can filter collections by care level, light, pet-safe and more (filters are configured by you in Search & Discovery; the theme renders them).

### Editorial design system

- Warm, biophilic "calm botanical magazine" look: oat / cream / clay backgrounds, sage and forest-green accents, terracotta and bloom highlights, organic rounded and leaf-shaped corners. Designed from the ground up for this niche — not a recolor.
- Default type pairing: **Fraunces** (soft old-style serif) for headings with **Work Sans** (humanist sans) for body — all swappable via the font picker.

### General storefront features

- **Online Store 2.0 throughout** — every template is JSON/section-based, so you can add, remove and reorder sections (and use app blocks) in the theme editor.
- **8 built-in color schemes** — recolor any section independently via per-section color-scheme settings.
- **`font_picker` typography** — heading, subheading and body fonts are chosen from Shopify's hosted font library (Google Fonts + system fonts). No third-party font loading, fast and license-clean.
- **Rich-media product gallery** — product media supports images, video, external video (YouTube / Vimeo) and 3D models, with image focal-point support and an organic leaf-masked gallery layout.
- **Predictive search** — instant search-as-you-type suggestions for products, collections, pages and articles.
- **Variant swatches** — color/finish and pot/size variants render as swatches, ideal for plant sizes and planter options.
- **Mobile sticky add-to-cart** — a pinned add-to-cart bar with quantity and live price on mobile product pages.
- **Cart drawer + accelerated checkout** — slide-out cart with dynamic checkout (Shop Pay) buttons.
- **Subscription selector** — the product page renders a "one-time vs Subscribe & Save" purchase toggle when a product has selling plans (see Compatibility — needs a subscription app to create the plans).
- **Gift cards** — a styled gift-card template with QR code for in-store redemption.
- **Accessibility** — semantic landmarks, visible focus states, ARIA labels, reduced-motion support, and unique element IDs.
- **Performance** — lazy-loaded responsive images, lightweight first-party JavaScript (no heavyweight frameworks), and section-scoped CSS.
- **Translation-ready** — full storefront and theme-editor schema localization (two-layer i18n), shipping with English.

---

## What's included

**Templates** (all Online Store 2.0)

- Home (`index`)
- Product
- Collection
- Collection list (`list-collections`)
- Cart
- Search
- Blog & Article
- Page, About page, Contact page
- Password
- Gift card
- Customer account set: login, register, account, addresses, order, activate account, reset password
- 404

**~45 sections**, including the niche set — botanical hero, plant-care panel, care finder, care guide, lookbook, product facts — plus the core library: header, footer, announcement, slideshow, hero, featured products, collection list, editorial split, multicolumn, rich text, FAQ, reviews, logo list, newsletter, newsletter popup, promise / trust / subscribe bars, product recommendations, custom Liquid, cart drawer, and all the `main-*` template sections.

Plus reusable snippets (product card, cart line, variant swatch, search modal, icons, structured data) and section groups for the header and footer.

---

## Installation

1. Download the theme `.zip` you received.
2. In your Shopify admin, go to **Online Store › Themes**.
3. Click **Add theme › Upload zip file**, select the Verdant `.zip`, and upload.
4. Once it appears in your theme library, use **Customize** to set it up, then **Actions › Publish** to make it live.

> Tip: customize and preview Verdant as an unpublished theme first, then publish when you're happy.

---

## Demo content & images

The theme ships with **placeholder demo images** so the homepage and product pages look designed out of the box. These placeholders are not licensed for your live store — replace them with your own brand photography.

- A full image **art-direction pack** is included with the theme (`prompts.txt`) — it lists every image slot with its exact filename, pixel size, aspect ratio, and a ready-to-use generation prompt, all tuned to Verdant's warm botanical look. Use it to generate or brief a cohesive image set (hero, lookbook, reviews, newsletter, product and collection photography).
- **Products and collections are yours.** The demo store shows example plants (Monstera, Pothos, Snake plant, etc.), but you create your own products, collections, prices and inventory in Shopify admin. Upload product media in **Products**, and collection banners in **Collections**.
- For the **plant-care spec panel**, you can either type values directly into each spec block, or set up product metafields (e.g. `custom.light`, `custom.water`, `custom.humidity`, `custom.difficulty`, `custom.mature_size`, `custom.hardiness_zone`) and reference the key in each block to drive specs per product.

---

## Customization

Everything is configured visually in the theme editor (**Online Store › Themes › Customize**) — no code required.

**Theme settings (global)**

- **Colors** — 8 color schemes you can edit; assign a scheme per section.
- **Typography** — pick heading, subheading and body fonts from the font picker.
- **Layout** — logo, favicon, page width, spacing, corner radius, buttons and other global styling.

**Per-section settings**

Each section has its own settings — headings, eyebrows, text, images, color scheme, columns/alignment, and block-level controls. For example:

- *Plant-care panel*: add/remove spec rows, pick icons and tones, set the difficulty meter, attach metafield keys.
- *Care finder*: add tiles, choose icons/colors, set the collection link for each.
- *Care guide*: write numbered steps with icons and rich text, add an image and CTA.

Reorder, add or remove sections freely; add app blocks where supported.

---

## Compatibility

- **Online Store 2.0** — required (sections everywhere, app blocks, metafields).
- **No app required for core features** — the theme's design, navigation, cart, gallery, predictive search, gift cards, sticky add-to-cart, and the plant-care panel/care-finder/care-guide sections all work out of the box.
- **Honest "needs an app" notes** (the theme renders the UI; the app provides the data/feature):
  - **Care-based collection filters** need Shopify's free **Search & Discovery** app to define the filters; the theme renders whatever filters you enable there.
  - **Subscriptions / Subscribe & Save** — the product page shows a one-time vs subscribe selector only when a product has selling plans, which requires a **subscription app** to create. The theme is subscription-*ready*, not a subscription engine.
  - **Plant-care reminders / email care series** are not part of the theme; use a marketing/automation app if you want them.
  - **Product reviews / star ratings** — the reviews section displays curated testimonials; for verified, automated review collection use a reviews app.
- Works with the standard Shopify checkout and Shop Pay accelerated checkout.

---

## Support

Questions, setup help, or something not working as expected?

**Email:** blackdynamic.corporate@gmail.com

When you write in, include your store URL and a description (a screenshot helps) so we can help faster.

---

## Changelog

### v1.0.0
- Initial release of Verdant.
- Botanical "calm magazine" design system with 8 color schemes and Fraunces + Work Sans typography.
- Niche sections: botanical hero, plant-care spec panel (metafield-driven), care finder, care guide, lookbook, product facts.
- Full Online Store 2.0 template set, rich-media product gallery, predictive search, variant swatches, mobile sticky add-to-cart, cart drawer, gift cards, subscription-ready product page.
- Accessibility, performance and full two-layer (storefront + schema) localization.

---

*Verdant is an original theme by Black Dynamic.*
