# ✨ Shreya's Portfolio

A personal portfolio website — old money elegance meets Gen Z energy.

**Live at:** `https://YOUR-USERNAME.github.io/portfolio/`

---

## 🚀 How to Host on GitHub Pages (Step by Step)

### 1. Create a GitHub Account (skip if you have one)
- Go to [github.com](https://github.com) and sign up

### 2. Create a New Repository
- Click the **+** button (top right) → **New repository**
- **Repository name:** `portfolio` (or `your-username.github.io` for a custom domain)
- Set it to **Public**
- Check **"Add a README file"** (optional, we'll replace it)
- Click **Create repository**

### 3. Upload Your Files
**Option A: Through the GitHub website (easiest)**
1. Open your new repo on GitHub
2. Click **"Add file"** → **"Upload files"**
3. Drag and drop the `index.html` file
4. Write a commit message like "Initial portfolio upload"
5. Click **"Commit changes"**

**Option B: Using Git on your computer**
```bash
# Clone the repo
git clone https://github.com/YOUR-USERNAME/portfolio.git
cd portfolio

# Copy your index.html into this folder, then:
git add .
git commit -m "Initial portfolio upload"
git push origin main
```

### 4. Enable GitHub Pages
1. Go to your repo on GitHub
2. Click **Settings** (gear icon, top menu)
3. In the left sidebar, click **Pages**
4. Under **Source**, select **Deploy from a branch**
5. Under **Branch**, choose `main` and folder `/ (root)`
6. Click **Save**
7. Wait 1-2 minutes, then visit: `https://YOUR-USERNAME.github.io/portfolio/`

### 5. Custom Domain (Optional)
If you own a domain (e.g., `shreya.dev`):
1. In **Settings → Pages**, type your domain under "Custom domain"
2. Add a CNAME record at your domain registrar pointing to `YOUR-USERNAME.github.io`

---

## ✏️ How to Customize

Open `index.html` in any text editor and update:

| What to change | Search for | Replace with |
|---|---|---|
| Email address | `your.email@example.com` | Your actual email |
| LinkedIn URL | `https://linkedin.com/in/your-profile` | Your LinkedIn URL |
| GitHub URL | `https://github.com/your-username` | Your GitHub URL |
| Medium URL | `https://medium.com/@your-handle` | Your Medium URL |
| Medium article links | `href="#"` on article cards | Actual Medium article URLs |
| Article dates | `Dec 2025`, `Jan 2026`, etc. | Real publication dates |
| Profile text | Any text in the About section | Your preferred wording |

---

## 📁 Structure

```
portfolio/
├── index.html      ← Everything lives in one file (HTML + CSS + JS)
└── README.md       ← This file
```

Single-file architecture = zero build steps, instant GitHub Pages deploy.

---

## 🎨 Design Details

- **Fonts:** Playfair Display (display) + Outfit (body) + DM Mono (accents)
- **Palette:** Cream, charcoal, warm gold, sage, navy
- **Effects:** CSS grain overlay, scroll-reveal animations, hover states
- **Responsive:** Works on desktop, tablet, and mobile

Built with love and a questionable amount of CSS. ☕
