# 偉唱冷氣水電裝飾工程有限公司 Wai Cheong Air Condition Water Electric Decoration Engineering Ltd. Website

Static marketing website for 偉唱冷氣水電裝飾工程有限公司 (Wai Cheong Air Condition Water Electric Decoration Engineering Ltd.),
a Hong Kong-based air-conditioning maintenance and repair company. The experience is fully localised in Traditional Chinese
and showcases the modern Version 2 layout with glassmorphism styling, KPI highlights, and consistent CTA banners across
every page.

## Getting Started

Open `index.html` in any modern browser to preview the homepage. The navigation menu links to the other sections:

- `services.html` – 維修保養方案與價格
- `cases.html` – 歷史項目亮點
- `vendors.html` – 合作供應商名單
- `contact.html` – Contact 與支援資訊

### Customising the Hero Image

Replace `assets/img/hero-placeholder.svg` with your preferred hero photograph. Keep the same filename to preserve the styling,
or update the background image path inside the stylesheet under the `.site-header` or `.page-header::after` rules.

### Updating Copy & Highlights

- Hero bullet copy lives in `index.html` inside the `<aside class="hero-highlights">` element.
- Company metrics live in the `section.highlight-metrics` block on the homepage.
- CTA banners reuse the `.cta-banner` class on every page.

## Structure

```
assets/
  css/style.css     # Global styles, layout, and reusable components
  img/hero-placeholder.svg
index.html          # Homepage with hero, programmes, metrics, testimonials
services.html       # Services, pricing tiers, visit inclusions
cases.html          # Case studies / historical projects
vendors.html        # Vendor partners list
contact.html        # Contact information and enquiry form
```

All typography uses Google Fonts (`Noto Sans TC` and `Roboto`) loaded via CDN.
