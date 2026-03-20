# DevOps Engineer Portfolio

A production-grade, fully responsive portfolio website built with pure HTML, CSS, and Vanilla JS.  
Ready to deploy on **GitHub Pages** in under 2 minutes.

---

## 📁 Project Structure

```
devops-portfolio/
├── index.html              ← Main HTML (all sections)
├── assets/
│   ├── css/
│   │   └── style.css       ← All styles + responsive breakpoints
│   └── js/
│       └── main.js         ← Scroll reveal, counters, filter, nav
└── README.md
```

---

## 🚀 Deploy to GitHub Pages

### Step 1 — Create a new GitHub repository
1. Go to [github.com/new](https://github.com/new)
2. Name it `devops-portfolio` (or `yourusername.github.io` for a root domain)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Push the code
```bash
cd devops-portfolio

git init
git add .
git commit -m "Initial portfolio deploy"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/devops-portfolio.git
git push -u origin main
```

### Step 3 — Enable GitHub Pages
1. Open your repository on GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select `Deploy from a branch`
4. Choose branch: `main`, folder: `/ (root)`
5. Click **Save**

### Step 4 — Visit your live site
```
https://YOUR_USERNAME.github.io/devops-portfolio/
```
It usually goes live within **1–2 minutes**.

---

## ✏️ Personalise Before Deploying

Open `index.html` and update these placeholders:

| What to change | Where to find it |
|---|---|
| Your name / title | `<h1 class="hero-name">` in `#hero` |
| Email address | `<a href="mailto:...">` in `#contact` |
| LinkedIn URL | `<a href="https://linkedin.com/...">` in `#contact` |
| GitHub URL | `<a href="https://github.com/...">` in `#contact` |
| Quick stats terminal | `.quick-stats` block in `#contact` |

---

## 🎨 Features

- ⚡ **No dependencies** — pure HTML / CSS / JS, no build step required
- 📱 **Fully responsive** — mobile, tablet, desktop
- 🌙 **Dark cyber theme** — JetBrains Mono + Bebas Neue typography
- ✨ **Scroll-reveal animations** with IntersectionObserver
- 🔢 **Animated stat counters** that trigger on scroll
- 🗂️ **Project filter tabs** — filter by category
- 🖥️ **Animated terminal** in the hero section
- 🔘 **Scroll-dot navigation** with section tracking
- 📐 **5-column tech stack** with skill bars

---

## 🛠️ Tech Stack Used to Build This

| Tool | Purpose |
|---|---|
| HTML5 (semantic) | Markup |
| CSS3 (custom properties, grid, flexbox) | Layout & styling |
| Vanilla JavaScript (ES5 compatible) | Interactions |
| Google Fonts | Typography |
| GitHub Pages | Hosting |

---

## 📄 License

MIT — free to use and customise.
