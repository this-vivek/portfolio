# Vivek Rawat — Data Engineer Portfolio

Responsive, glass-morphism portfolio built with **HTML, CSS, and JavaScript**.  
Showcases my projects across **Azure, Databricks, PySpark, Delta**, real-time streaming, and **data governance (Purview)**. Deployed with **GitHub Pages**.

> **Live Site:** https://<your-username>.github.io/<your-repo>/  
> **Repo:** https://github.com/<your-username>/<your-repo>

---

## ✨ Features

- Dark gradient theme with glass cards and corporate typography  
- **Sticky header** with brand name that **shrinks on scroll**  
- **Smooth scroll** with gentle **section snap** + subtle **parallax**  
- **Mobile-first** collapsible section headers (About, Skills, Projects, Experience, Contact)  
- **Scroll-reveal** animations (re-triggers on scroll up)  
- **Responsive profile image** (round, border, shadow)  
- Skills grid with icons; Projects grid with tags  
- Zero frameworks, zero build step — just open `index.html`

---

## 🧰 Tech Stack

- **HTML5**, **CSS3**, **JavaScript (ES6)**  
- Hosting: **GitHub Pages**  
- No frameworks, no bundlers

---

## 🗂️ Structure

/
├─ index.html
└─ images/
└─ vivek.jpg # your profile photo (replace with your file)

> All assets are referenced with **relative paths** so it works locally and on GitHub Pages.

---

## 📦 Getting Started (Local)

1. Download or clone the repository.
2. Open `index.html` in your browser.  
   *(Optional)* Use VS Code “Live Server” for auto-reload.

---

## 🚀 Deploy to GitHub Pages (UI)

1. Push `index.html` and your `images/` folder to a GitHub repo.  
2. Repo → **Settings** → **Pages**.  
3. **Source:** *Deploy from a branch* → **Branch:** `main` → **Folder:** `/ (root)` → **Save`.  
4. Your site will be live at:  
   `https://<your-username>.github.io/<your-repo>/`

> If you use folders that start with `_`, add a file named `.nojekyll` at the repo root (prevents Jekyll from ignoring them).

---

## 🧑‍🎨 Customize

- **Name in header:** search for `.brand .name` in `index.html`.
- **Profile image:** place your photo at `images/vivek.jpg` (or any name) and update:
  ```html
  <img src="./images/vivek.jpg" alt="Vivek Rawat">
