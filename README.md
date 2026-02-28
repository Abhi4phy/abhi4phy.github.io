# Abhishek Yadav — Portfolio & CV

A modern, responsive personal portfolio and downloadable CV built with HTML, CSS, and vanilla JavaScript.

🔗 **Live Site:** [abhi4phy.github.io](https://abhi4phy.github.io)

---

## ✨ Features

- **Full-screen hero** with gradient background and call-to-action buttons
- **Sticky glassmorphism navbar** with mobile hamburger menu
- **Timeline layout** for Experience & Education sections
- **Skill cards** with icons and pill-shaped tags
- **Reference cards** with hoverable email buttons
- **Language proficiency bars** with gradient fills
- **Scroll-triggered fade-in animations** via Intersection Observer
- **Downloadable CV** — print-optimized page that exports cleanly to PDF
- Fully **responsive** on mobile, tablet, and desktop

## 📁 Project Structure

```
abhi4phy.github.io/
├── index.html              # Main portfolio / landing page
├── style.css               # All styles for the portfolio
├── cv.html                 # Print-optimized CV (browser-based PDF)
├── Abhishek_Yadav_CV.tex   # LaTeX source for the CV
├── Abhishek_Yadav_CV.pdf   # Compiled PDF (downloadable from the site)
└── README.md               # This file
```

## 🛠️ Tech Stack

| Layer      | Details                                         |
|------------|--------------------------------------------------|
| Markup     | HTML5, semantic sections                         |
| Styling    | CSS3 — Grid, Flexbox, CSS variables, animations  |
| Typography | [Inter](https://fonts.google.com/specimen/Inter) via Google Fonts |
| Icons      | [Font Awesome 6](https://fontawesome.com/)       |
| JavaScript | Vanilla JS — Intersection Observer, smooth scroll |

## 📄 Downloading the CV as PDF

### Option 1 — Direct download (recommended)
Click the **"CV"** button in the site's navbar. It downloads `Abhishek_Yadav_CV.pdf` directly.

### Option 2 — Browser print
1. Open [cv.html](cv.html) in a browser (or click it from the live site).
2. Press `Ctrl + P` → set destination to **"Save as PDF"** → save.

### Re-compiling from LaTeX
```bash
pdflatex Abhishek_Yadav_CV.tex
```
Requires a TeX distribution (MiKTeX, TeX Live, etc.) with `fontawesome5` package.

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Abhi4phy/abhi4phy.github.io.git

# Open in browser
start index.html   # Windows
open index.html     # macOS
```

No build step or dependencies required — it's pure HTML/CSS/JS.

## 👤 About

**Abhishek Yadav** — Computational Physicist & Researcher  
Ph.D. Scholar, UM-DAE CEBS, Mumbai

- 📧 yadavabhishek711@gmail.com
- 🔗 [LinkedIn](https://www.linkedin.com/in/abhi1yadav/)
- 💻 [GitHub](https://github.com/Abhi4phy)

## 📜 License

Feel free to use this template for your own portfolio/CV — just replace the personal information with your own.
