# CoolCare Air Website

Static marketing website for a Hong Kong-based air-conditioning maintenance and repair company. The experience is fully
localised in Traditional Chinese and showcases the modern Version 2 layout with glassmorphism styling, KPI highlights, and
consistent CTA banners woven throughout a single scrolling page.

## Getting Started

Open `index.html` in any modern browser to preview the homepage. The navigation menu uses in-page anchors that smoothly
scroll to each content block:

- `#services` – 維修保養方案、方案價目與到訪項目
- `#cases` – 歷史項目亮點與成效
- `#vendors` – 合作供應商名單
- `#contact` – Contact 與支援資訊

### Customising the Hero Image

Replace `assets/img/hero-placeholder.svg` with your preferred hero photograph. Keep the same filename to preserve the styling,
or update the background image path inside the stylesheet under the `.site-header` rule.

### Updating Copy & Highlights

- Hero bullet copy lives in `index.html` inside the `<aside class="hero-highlights">` element.
- Company metrics live in the `section.highlight-metrics` block on the homepage.
- CTA banners reuse the `.cta-banner` class across multiple sections of the homepage.

## Structure

```
assets/
  css/style.css     # Global styles, layout, and reusable components
  img/hero-placeholder.svg
index.html          # Single-page experience with hero、方案、案例、供應商與聯絡部分
```

All typography uses Google Fonts (`Noto Sans TC` and `Roboto`) loaded via CDN.
