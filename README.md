# TryNFits — Try Before You Buy Platform

**Chennai & Lagos · India & Nigeria**

A complete try-before-you-buy fashion delivery platform. Customers try up to 3 outfits at home for 45 minutes and pay only for what they keep.

---

## 🌐 Live Portals

| File | Portal | Who Uses It |
|------|--------|-------------|
| `index.html` | Customer · Shop Owner · Delivery Partner | Public users |
| `admin.html` | Admin · Operations | Internal team only |

---

## 🚀 Deploy to Netlify via GitHub

### Step 1 — Push to GitHub
```bash
# In your terminal
git init
git add .
git commit -m "TryNFits initial deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/trynfits.git
git push -u origin main
```

### Step 2 — Connect Netlify
1. Go to [app.netlify.com](https://app.netlify.com)
2. Click **"Add new site" → "Import an existing project"**
3. Choose **GitHub** → select your `trynfits` repo
4. Build settings:
   - **Build command:** *(leave empty)*
   - **Publish directory:** `.` *(just a dot)*
5. Click **Deploy site**

### Step 3 — Your site goes live!
- Main: `https://your-site.netlify.app` → Customer/Shop/Rider portal
- Admin: `https://your-site.netlify.app/admin.html` → Admin & Ops

---

## ✨ Features

### Customer Portal
- Browse 5 boutiques, 8+ products
- Filter by category, search by name
- Add up to 3 items to Try List
- Full order flow: Cart → Address → Deposit → Tracking → Try Session → Complete
- 45-minute live countdown timer
- Keep/return selector with live total
- Order history

### Shop Owner Portal
- Dashboard with revenue, commission, net payout
- Full product CRUD — add, edit, hide, delete
- Image/emoji upload for products
- Order tracking with live timer
- Earnings breakdown
- Shop profile editor with logo upload

### Delivery Partner Portal
- Go online/offline toggle
- Active order with step-by-step status updates
- Photo upload for pickups
- Earnings breakdown
- Rules & SOP

### Admin Portal
- Platform overview with animated revenue chart
- Shop management: approve/reject/suspend + full CRUD + logo upload
- Product management: search, filter, toggle, delete
- Order management: assign riders, view details, mark complete
- Rider management: full CRUD + KYC document upload
- Customer directory
- Live config editor (deposit, fees, try window, commission, zones)

### Operations Portal
- Live order monitor with urgency alerts
- Issue tracking & escalation with photo evidence upload
- Dispatch board — assign riders to unassigned orders
- Full SOP library (5 scenarios, collapsible)

---

## 💱 Currency
Toggle between ₹ INR (India) and ₦ NGN (Nigeria) on any screen. All prices update instantly.

---

## 🛠 Tech Stack
Pure HTML + CSS + Vanilla JavaScript. No frameworks, no build step, no dependencies.
Zero configuration needed — just static files.

---

## 📁 File Structure
```
trynfits/
├── index.html        ← Customer / Shop / Rider portal
├── admin.html        ← Admin / Operations portal
└── README.md         ← This file
```

---

## 🔗 Cross-portal Links
- From `index.html` sidebar: link to `admin.html`
- From `admin.html` role screen: link to `index.html`

---

*Built with ❤️ for Chennai & Lagos*
