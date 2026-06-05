# 🪡 Nelo House of Fashion — Landing Page

**Official website for Nelo House of Fashion (NHF)**
Luxury bespoke tailoring by **Chinelo Chukwurah** — Independence Layout, Enugu, Nigeria.

> Built with pure HTML, CSS, and JavaScript. No frameworks, no dependencies, no build step required. All images are embedded directly in the HTML — the entire site is one self-contained file.

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
├── index.html      ← The entire website — HTML, CSS, JS, and all images in one file
└── README.md
```

That's it. No images folder, no separate assets, no build step.

---

## 🚀 Deployment (Free — GitHub + Cloudflare Pages)

### Step 1: Push to GitHub

1. Go to [github.com](https://github.com) and sign in
2. Click **New Repository** → name it `nelo-house-of-fashion` → set to **Public** → **Create**
3. On the repo page click **uploading an existing file**
4. Drag and drop `index.html` and `README.md` → **Commit changes**

---

### Step 2: Deploy to Cloudflare Pages

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com) → sign up free
2. Click **Create a project** → **Connect to Git** → authorise GitHub
3. Select `nelo-house-of-fashion`
4. Build settings:

| Setting | Value |
|---|---|
| Production branch | `main` |
| Build command | *(leave blank)* |
| Build output directory | `/` |

5. Click **Save and Deploy**

Site goes live at `nelo-house-of-fashion.pages.dev` within a minute.

---

### Step 3: Auto-deploy on every update

Every `git push` to `main` triggers an automatic redeploy. To update the site:

```bash
git add .
git commit -m "Update"
git push
```

---

*© 2025 Nelo House of Fashion. All rights reserved.*
