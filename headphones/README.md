# 🎧 Headphones Landing Page – ALX Front-End Project

![Project Banner](https://via.placeholder.com/1000x400?text=Headphones+Landing+Page)  
*Responsive, accessible, and built from scratch — no frameworks, no JavaScript (until Task 8)!*

---

## 📌 Overview

This project is part of the **ALX Front-End Web Development** curriculum. The goal is to implement a **fully responsive, accessible, and pixel-perfect landing page** for a fictional premium headphones brand, based on a professional **Figma design** by [Nicolas Philippot](https://www.figma.com/@nicolasphilippot).

The page includes:
- A modern **header/hero section**
- **"What we do..."** with custom icon fonts
- **"Our results"** with pure CSS pentagons (no images!)
- A functional **contact form**
- A clean **footer**
- Smooth **animations** and **mobile-first responsiveness**
- A **hamburger menu** for mobile navigation (with vanilla JavaScript)

All built **from scratch** using only **HTML, CSS, and minimal vanilla JS** — **no external libraries or frameworks** like Bootstrap.

---

## 🎯 Learning Objectives

- ✅ Translate Figma designs into semantic HTML & CSS  
- ✅ Master **responsive design** with media queries (mobile breakpoint: `480px`)  
- ✅ Implement **CSS variables**, **reset styles**, and **modular architecture**  
- ✅ Use **custom icon fonts** and **pure CSS shapes** (pentagons!)  
- ✅ Apply **accessibility best practices** (ARIA, semantic tags, focus states)  
- ✅ Add subtle **CSS animations** for enhanced UX  
- ✅ Build a **mobile hamburger menu** with vanilla JavaScript  

---

## 📁 Project Structure

```
alx_html_css/
└── headphones/
    ├── README.md
    ├── images/                  # All provided assets (logos, icons, etc.)
    ├── fonts/                   # Custom fonts: Source Sans Pro & Spin Cycle OT
    ├── holberton_school-icon/   # Custom icon font files
    │
    ├── 0-index.html             # Header / Hero section
    ├── 0-styles.css
    │
    ├── 1-index.html             # "What we do..." section
    ├── 1-styles.css
    │
    ├── 2-index.html             # "Our results" section
    ├── 2-styles.css
    │
    ├── 3-index.html             # Contact form
    ├── 3-styles.css
    │
    ├── 4-index.html             # Full page (with footer)
    ├── 4-styles.css
    │
    ├── 6-index.html             # "Our results" with CSS-only pentagons
    ├── 6-styles.css
    │
    ├── 7-index.html             # Animated sections
    ├── 7-styles.css
    │
    ├── 8-index.html             # Mobile hamburger menu (with JS)
    ├── 8-styles.css
    └── 8-script.js
```

---

## 🖼️ Design Reference

- **Figma File**: [Headphones Landing Page by Nicolas Philippot](https://www.figma.com/file/...)  
- **Fonts**:
  - **Headings**: [Spin Cycle OT](https://www.dafont.com/spin-cycle-ot.font)
  - **Body**: [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro)
- **Icons**: Custom `holberton_school-icon` font (provided)

> 💡 **Note**: If fonts don’t load locally, the page gracefully falls back to system fonts.

---

## 📱 Responsiveness

- **Desktop**: Full layout (max-width: `1000px`, centered)
- **Mobile**: Activates at **≤ 480px**
  - Hamburger menu replaces navigation
  - Stacked content layout
  - Touch-friendly buttons and inputs

### Interactive States
- **Links**: Hover/active color → `#FF6565`
- **Buttons**: Hover/active → `opacity: 0.9`

---

## 🧪 How to View

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/alx_html_css.git
   cd alx_html_css/headphones
   ```
2. Open any `*-index.html` file in your browser (e.g., `4-index.html` for the complete page).
3. Resize your browser to test responsiveness.
4. For the hamburger menu (Task 8), open `8-index.html`.

---

## 🛠️ Tech Stack

- **HTML5** – Semantic structure
- **CSS3** – Flexbox, Grid, Variables, Animations, Media Queries
- **Vanilla JavaScript** – Only for Task 8 (hamburger toggle)
- **Custom Icon Font** – For "What we do..." section
- **Pure CSS** – Pentagons drawn with `clip-path` or `transform` (no images!)

---

## 📝 Notes

- All tasks are **incremental**: each builds on the previous.
- **No external CSS frameworks** allowed (e.g., Bootstrap, Tailwind).
- **JavaScript is forbidden** until Task 8.
- **Accessibility** is prioritized: proper contrast, semantic tags, keyboard navigability.

---

## 🏆 Completion

✅ This project marks the **end of the HTML & CSS block** in the ALX Front-End program.  
🎉 Celebrate your milestone — you’ve built a professional-grade landing page **from design to code!**

---

> **Copyright © 2025 ALX. All rights reserved.**  
> Designed by Nicolas Philippot | Developed by [Your Name]