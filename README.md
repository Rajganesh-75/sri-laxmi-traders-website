# Sri Laxmi Traders — B2B Textile Wholesale Website

Premium B2B textile wholesale website with **live product catalog powered by Google Sheets**.

🌐 **Live:** [sri-laxmi-traders.pages.dev](https://sri-laxmi-traders.pages.dev)  
🎨 **Design:** Warm Gold Light Theme · Instrument Serif + Archivo · Floating Fabric Cards · Woven Thread Background  

---

## 🚀 Deploy to Cloudflare Pages

1. Push this repo to GitHub
2. Go to [Cloudflare Pages](https://dash.cloudflare.com/) → Workers & Pages → Create
3. Connect GitHub → Select this repo
4. Settings:
   - Build command: *(leave empty)*
   - Build output directory: `/`
5. Deploy!

---

## 📊 Google Sheets — Product Catalog

Products are managed via a Google Sheet. No code changes needed to add/edit/remove products.

**Sheet ID:** `19xNH0TVdHvwFLFU2pwcpe6XqriAoAdZH_S2bGv0XvDc`

### Sheet Columns

| A | B | C | D | E |
|---|---|---|---|---|
| **Home Page** | **Product Name** | **Category** | **Description** | **Image URL** |

### Column Details

| Column | What to enter |
|--------|--------------|
| **A — Home Page** | `*` = show on homepage, `**` = new collection, *empty* = collection page only |
| **B — Product Name** | e.g. "Cotton Multi Batik" |
| **C — Category** | One of: `Cotton`, `Cotton Handloom`, `Rayon`, `Silk Chandheri` |
| **D — Description** | Product description text |
| **E — Image URL** | GitHub raw link or Google Drive share link |

### Adding a New Product

1. Open the [Google Sheet](https://docs.google.com/spreadsheets/d/19xNH0TVdHvwFLFU2pwcpe6XqriAoAdZH_S2bGv0XvDc/edit)
2. Add a new row:

| A | B | C | D | E |
|---|---|---|---|---|
| * | Blue Floral Cotton Batik | Cotton | Vibrant blue floral batik print on premium cotton | https://github.com/Rajganesh-75/... |

3. The product appears automatically on the website within minutes!

### Image URLs

Upload product images to this GitHub repo or use Google Drive:

**GitHub (recommended):**
```
https://github.com/Rajganesh-75/sri-laxmi-traders-website/blob/main/assets/your-image.jpg
```
The website automatically converts this to a raw URL.

**Google Drive:**
Share the image → Copy link → Paste the share URL. The website converts it automatically.

---

## 📁 Project Structure

```
sri-laxmi-traders-website/
├── index.html              ← Homepage (hero, products, services, testimonials, about, contact)
├── collection.html         ← Full product catalog (Google Sheets powered)
├── cotton-handloom.html    ← Cotton Handloom category page
├── cotton-batik.html       ← Cotton Batik category page
├── rayon.html              ← Rayon category page
├── silk-chandheri.html     ← Silk Chandheri category page
├── assets/
│   ├── logo-emblem.png     ← Nav + footer logo
│   ├── logo.png            ← Backup logo
│   ├── weaving.mp4         ← About section weaving video
│   ├── handloom-cotton.jpg ← Homepage hero + category card
│   ├── cotton-tye-dye-batik.jpg
│   ├── rayon-white-batik.jpg
│   ├── jaquard-chandheri.jpg
│   └── new-collection-chandheri.jpg
└── README.md
```

---

## ✨ Features

- ✅ **Warm gold light theme** — clean, premium textile feel
- ✅ **Floating fabric cards** — 5 animated product showcases in hero
- ✅ **Woven thread canvas background** — subtle animated golden threads + particles
- ✅ **Google Sheets CMS** — add/edit products from phone, no coding needed
- ✅ **WhatsApp integration** — contact form sends to WhatsApp, inquiry buttons on all products
- ✅ **6-page structure** — homepage + collection + 4 category pages
- ✅ **Instrument Serif + Archivo** — clean editorial typography (weight 400)
- ✅ **Fully responsive** — mobile, tablet, desktop
- ✅ **Scroll reveal animations** — sections animate on scroll
- ✅ **Parallax orbs** — floating gradient background effects
- ✅ **SEO optimized** — meta tags, semantic HTML
- ✅ **Fast loading** — static site, no build step
- ✅ **Free hosting** — Cloudflare Pages

---

## 📞 Contact Details (in website)

| Detail | Value |
|--------|-------|
| **Phone** | +91 9364110190 / +91 9994685686 |
| **WhatsApp** | +91 9364110190 |
| **Address** | 63, Thillai Nagar, Near IOB Bank, Erode - 638001, Tamil Nadu |
| **Hours** | Mon - Sat: 9:00 AM - 7:00 PM |

---

## 📄 License

© 2026 Sri Laxmi Traders. All Rights Reserved.
