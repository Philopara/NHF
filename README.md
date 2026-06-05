# 🪡 Nelo House of Fashion — Landing Page

**Official website for Nelo House of Fashion (NHF)**  
Luxury bespoke tailoring by **Chinelo Chukwurah** — Independence Layout, Enugu, Nigeria.

> Built with pure HTML · CSS · JavaScript. No frameworks, no dependencies, no build step required.

---

## 🌐 Live URL

Once deployed, update this line with the live URL:
```
https://nelo-house-of-fashion.pages.dev
```

---

## 📁 Project Structure

```
nelo-house-of-fashion/
├── index.html          ← The entire website (single file)
├── images/             ← Add real photos here (see below)
│   └── .gitkeep
├── README.md
└── .gitignore
```

---

## 📸 Adding Real Photos

Placeholder sections are clearly marked with `TODO` comments in `index.html`.  
Add photos to the `/images/` folder, then update the HTML:

| Section | File name suggestion | Size |
|---|---|---|
| Hero background | `images/hero.jpg` | 1600×900px min |
| About (Chinelo portrait) | `images/chinelo.jpg` | 600×800px min |
| Gallery 1 — Bridal | `images/gallery-bridal.jpg` | 800×800px |
| Gallery 2 — Corporate | `images/gallery-corporate.jpg` | 800×600px |
| Gallery 3 — Traditional | `images/gallery-traditional.jpg` | 800×600px |
| Gallery 4 — Casual | `images/gallery-casual.jpg` | 800×600px |
| Gallery 5 — Atelier | `images/gallery-atelier.jpg` | 800×600px |

**To swap a placeholder**, find the relevant `TODO` block in `index.html` and replace:
```html
<!-- BEFORE (placeholder) -->
<div class="about-img-ph">…</div>

<!-- AFTER (real photo) -->
<img src="images/chinelo.jpg"
     alt="Chinelo Chukwurah, Founder of Nelo House of Fashion"
     class="about-img"
     loading="lazy">
```

---

## 💬 Adding Real Testimonials

In `index.html`, search for the comment:
```
TODO: Replace with real testimonials when received.
```
Update each `<article class="testi-card">` block with real client quotes, names, and descriptions.

---

## 🚀 Deployment (Free — Cloudflare Pages + GitHub)

### Step 1: Push to GitHub

1. Go to [github.com](https://github.com) → **New Repository**
2. Name it: `nelo-house-of-fashion`
3. Set it to **Public**
4. Click **Create Repository**
5. In your terminal (or GitHub Desktop), run:

```bash
cd nelo-house-of-fashion
git init
git add .
git commit -m "Initial commit — NHF landing page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/nelo-house-of-fashion.git
git push -u origin main
```

---

### Step 2: Deploy to Cloudflare Pages

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com) → Sign up / Log in (free)
2. Click **Create a project** → **Connect to Git**
3. Authorise GitHub and select `nelo-house-of-fashion`
4. Configure the build:

| Setting | Value |
|---|---|
| Project name | `nelo-house-of-fashion` |
| Production branch | `main` |
| Build command | *(leave blank)* |
| Build output directory | `/` |

5. Click **Save and Deploy**

✅ Your site will be live at: `https://nelo-house-of-fashion.pages.dev`

---

### Step 3: Auto-deploy on every update

Every time you `git push` to `main`, Cloudflare Pages automatically rebuilds and redeploys.  
That means adding photos, updating testimonials, or changing text is as simple as:

```bash
git add .
git commit -m "Added gallery photos"
git push
```

---

### Step 4 (Optional): Custom Domain

If Chinelo wants `www.nelohouseoffashion.com`:

1. Buy the domain at [namecheap.com](https://namecheap.com) (~₦15,000–₦25,000/year)
2. In Cloudflare Pages → **Custom Domains** → Add domain
3. Follow Cloudflare's DNS instructions — they walk you through it step by step

---

## 📋 Pending Updates

Track what still needs to be added:

- [ ] Hero background photo (real NHF shot)
- [ ] Chinelo portrait photo
- [ ] Gallery photos (5 minimum)
- [ ] Real client testimonials (3 minimum)
- [ ] Verify Google Maps pin is accurate
- [ ] Test WhatsApp click-to-chat on mobile
- [ ] Add custom domain (optional)

---

## ⚙️ Contact Form

The form currently routes submissions directly to WhatsApp — ideal for Nigerian businesses where WhatsApp is the primary communication channel. No back-end or email server needed.

**Want proper email delivery too?**  
Sign up for [Formspree](https://formspree.io) (free tier) and update the form action:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

---

## 🛠 Tech Stack

| | |
|---|---|
| Language | HTML5, CSS3 (custom properties), Vanilla JS |
| Fonts | Cormorant Garamond · Cormorant SC · DM Sans (Google Fonts) |
| Icons | Inline SVG (no external icon library) |
| Hosting | Cloudflare Pages (free) |
| Repo | GitHub |
| Build | None required — plain HTML |

---

*Built with care. © 2025 Nelo House of Fashion.*
