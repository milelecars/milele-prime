# Milele Prime — SEO Setup Checklist & Reference
Generated: June 2025

---

## ✅ ALREADY BUILT INTO YOUR WEBSITE

### Meta Tags (in <head>)
- [x] Title tag: "Milele Prime | Professional Forex & CFD Trading — MT5 Platform"
- [x] Meta description (unique per page via JS)
- [x] Meta keywords
- [x] Canonical URL: https://www.mileleprime.com/
- [x] Open Graph tags (og:title, og:description, og:image, og:url, og:type)
- [x] Twitter Card tags
- [x] Theme color: #0A0A0A
- [x] Schema.org FinancialService structured data (JSON-LD)

### Technical SEO
- [x] Favicon (32x32 PNG) — browser tab icon
- [x] Apple Touch Icon (180x180) — iOS home screen
- [x] Google Fonts with display=swap (render performance)
- [x] Preconnect links for fonts
- [x] Robots meta: index, follow
- [x] Responsive / mobile-first design
- [x] Fast loading (no heavy frameworks)

---

## 📂 FILES TO UPLOAD TO GITHUB ROOT

Upload these 3 files alongside your index.html:

| File | Purpose |
|------|---------|
| sitemap.xml | Tells Google all your pages |
| robots.txt | Tells crawlers what to index |
| index.html | Your main website file |

Your repo root should look like:
```
/
├── index.html        ← rename mileleprime_final.html to this
├── sitemap.xml
├── robots.txt
└── CNAME             ← auto-created by GitHub Pages (www.mileleprime.com)
```

---

## 🔧 AFTER YOU GO LIVE — DO THESE

### 1. Google Search Console
1. Go to → https://search.google.com/search-console
2. Add property: https://www.mileleprime.com
3. Verify via HTML tag OR DNS TXT record (GoDaddy)
4. Submit sitemap: https://www.mileleprime.com/sitemap.xml
5. Request indexing on the Coverage report

### 2. Google Analytics (optional)
1. Create account at → https://analytics.google.com
2. Get your Measurement ID (G-XXXXXXXXXX)
3. Add this before </head> in your index.html:
```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

### 3. Bing Webmaster Tools (optional but recommended)
1. Go to → https://www.bing.com/webmasters
2. Add site and submit sitemap

### 4. og:image (Social Sharing Preview)
Your Open Graph image URL is currently:
  https://www.mileleprime.com/og-image.png

You need to create and upload a 1200×630px PNG as og-image.png.
Recommended design: Dark background (#0A0A0A), Milele Prime logo centered,
tagline "Trade Smarter. Win Bigger." — white text on dark with violet glow.

---

## 📊 TARGET KEYWORDS (already in your meta)

Primary:
- forex broker
- MT5 broker
- CFD trading platform
- MetaTrader 5 broker
- ECN broker
- low spread forex

Long-tail:
- professional forex trading platform
- forex broker MT5 ECN spreads
- online CFD broker MetaTrader 5
- forex trading platform Dubai

---

## 🔗 SCHEMA.ORG (already embedded)

Your website includes FinancialService schema:
```json
{
  "@type": "FinancialService",
  "name": "Milele Prime",
  "url": "https://www.mileleprime.com",
  "description": "Professional forex and CFD broker on MetaTrader 5"
}
```
This helps Google show rich results for your business.

---

## ⚡ PERFORMANCE CHECKLIST

- [x] Google Fonts with display=swap
- [x] Preconnect to fonts.googleapis.com
- [x] No jQuery or heavy libraries
- [x] CSS animations (no heavy JS frameworks)
- [x] Images using content-visibility:auto
- [ ] Consider Cloudflare CDN once live (free tier)
- [ ] Enable GitHub Pages HTTPS (free SSL)

---

*File prepared by Claude for Milele Prime. Update lastmod dates in sitemap.xml whenever you publish major content changes.*
