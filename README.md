# Sri Laxmi Traders - B2B Textile Wholesale Website

A premium, modern B2B textile wholesale website with **live stock updates powered by Google Sheets**.

🌐 **Tech:** Static HTML/CSS/JS | Cloudflare Pages | Google Sheets CMS  
🎨 **Design:** Dark Luxury + Glassmorphism + 3D Background + Parallax  

---

## 🚀 Quick Start

### 1. Deploy to Cloudflare Pages
1. Push this repo to GitHub (`Rajganesh-75/sri-laxmi-traders-website`)
2. Go to [Cloudflare Pages](https://dash.cloudflare.com/) → Workers & Pages → Create
3. Connect GitHub → Select this repo
4. Settings:
   - Build command: *(leave empty)*
   - Build output directory: `/`
5. Deploy!

### 2. Set Up Google Sheets (Live Stock Updates)

This is how you update products from your phone/laptop without touching code:

#### Step 1: Create the Google Sheet

Create a new Google Sheet with these exact column headers in Row 1:

| A | B | C | D | E | F | G | H |
|---|---|---|---|---|---|---|---|
| Product Name | Category | Description | Status | Price | MOQ | Colors | Image URL |

#### Step 2: Fill in your products

Example rows:

| Product Name | Category | Description | Status | Price | MOQ | Colors | Image URL |
|---|---|---|---|---|---|---|---|
| Blue Floral Cotton Batik | Cotton Batik | Vibrant blue floral batik print on premium cotton | In Stock | ₹120/meter | 50 meters | Blue, Indigo | |
| Erode Handloom Saree Cotton | Cotton Handloom | Traditional Erode handloom cotton temple border | In Stock | ₹180/meter | 30 meters | White, Cream | |
| Digital Print Rayon Crepe | Rayon | Soft rayon crepe with trending digital prints | Limited | ₹95/meter | 100 meters | Multi-color | |
| Chanderi Silk Zari Border | Silk Chandheri | Pure Chanderi silk with golden zari border | On Program | ₹450/meter | 20 meters | Gold, Silver | |

**Status values (use exactly):**
- `In Stock` — Green badge
- `Limited` — Yellow badge
- `On Program` — Blue badge
- `Sold Out` — Red badge

**Category values (use exactly):**
- `Cotton Handloom`
- `Cotton Batik`
- `Rayon`
- `Silk Chandheri`

#### Step 3: Publish the Sheet

1. Open your Google Sheet
2. Go to **File → Share → Publish to web**
3. Select **Sheet1** (or your tab name)
4. Format: **Web page** (default is fine)
5. Click **Publish**
6. Copy the Sheet ID from your URL:
   ```
   https://docs.google.com/spreadsheets/d/THIS_IS_YOUR_SHEET_ID/edit
   ```

#### Step 4: Connect to Website

Open `index.html` and find this line (search for `YOUR_GOOGLE_SHEET_ID_HERE`):
```javascript
const SHEET_ID = 'YOUR_GOOGLE_SHEET_ID_HERE';
```
Replace with your actual Sheet ID:
```javascript
const SHEET_ID = '1aBcDeFgHiJkLmNoPqRsTuVwXyZ123456789';
```

#### Step 5: Done! 🎉

Now whenever you add/edit/remove rows in your Google Sheet, the website updates automatically!

---

## 📱 Your Daily Workflow

```
1. Open Google Sheet on phone/laptop
2. Add new row: "New Fabric Name | Cotton Batik | Description... | In Stock | ₹120/meter | 50 meters | Blue"
3. Website reflects the change within minutes!
4. To remove: Delete the row from the sheet
5. To mark sold out: Change Status column to "Sold Out"
```

---

## 📁 Project Structure

```
sri-laxmi-traders-website/
├── index.html              ← Main website (everything in one file)
├── assets/
│   └── images/             ← Add product/shop photos here
├── previews/               ← Design previews (can delete after launch)
└── README.md               ← This file
```

---

## ✏️ Customization Checklist

Before going live, update these placeholders in `index.html`:

| Find | Replace With |
|------|-------------|
| `YOUR_GOOGLE_SHEET_ID_HERE` | Your Google Sheet ID |
| `+91 98765 43210` | Your actual phone number |
| `+91 94321 56789` | Your second number (or remove) |
| `info@srilaxmitraders.com` | Your actual email |
| `123, Textilepuram, Brough Road` | Your actual address |
| Social media `#` links | Your Facebook/Instagram/YouTube URLs |

---

## ✨ Features

- ✅ Dark luxury glassmorphism design
- ✅ Three.js 3D animated background
- ✅ Parallax scroll effects
- ✅ Gold shimmer text animations
- ✅ **Live stock from Google Sheets** (no coding needed to update)
- ✅ Category filter for products
- ✅ Responsive (mobile + tablet + desktop)
- ✅ Contact form
- ✅ SEO optimized
- ✅ Fast loading (static site)
- ✅ Free hosting on Cloudflare Pages

---

## 📄 License

© 2024 Sri Laxmi Traders. All Rights Reserved.
