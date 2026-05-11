# Davivy — Perfume Landing Page

A professional, fully responsive landing page for **Davivy**, a luxury perfume brand. Built as part of a Frontend Developer Internship task.

---

## Project Overview

Davivy is a mock luxury perfume e-commerce landing page designed to showcase modern frontend development skills. The page features a sophisticated dark-and-gold aesthetic, smooth animations, and a fully responsive layout that adapts seamlessly across mobile, tablet, and desktop devices.

**Live Demo:** https://davivy1.github.io/Davivy-Perfumes---Landing-Page/

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic page structure |
| **CSS3** | Styling with Flexbox, CSS Grid, and custom properties |
| **JavaScript (Vanilla)** | Interactivity, mobile menu, scroll animations |
| **Google Fonts** | Playfair Display (headings) & Inter (body text) |
| **SVG Icons** | Lightweight, scalable icons (no external icon library) |

---

## Features

- **Responsive Design** — Fully adaptive across mobile, tablet, and desktop using CSS Grid, Flexbox, and media queries
- **Sticky Navigation** — Transparent navbar that transitions to a solid background on scroll
- **Mobile Hamburger Menu** — Slide-in navigation with smooth open/close transitions
- **Scroll Animations** — Cards fade in as they enter the viewport using Intersection Observer
- **Hover Effects** — Interactive buttons, cards, and social icons with smooth transitions
- **Smooth Scrolling** — Anchor links scroll smoothly to target sections
- **No External Dependencies** — Pure HTML, CSS, and JS with no frameworks or libraries

---

## Project Structure

```
davivy-landing-page/
├── index.html          # Main HTML file
├── styles.css          # All styles (responsive + animations)
├── script.js           # All JavaScript interactivity
└── README.md           # Project documentation
```

---

## Setup Instructions

### Option 1: Open Locally
Open `index.html` directly in your browser

### Option 2: Local Server 
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (npx)
npx serve .

# Using VS Code Live Server extension
# Right-click index.html → "Open with Live Server"
```
Then visit `http://localhost:8000`

### Option 3: Deploy
- **GitHub Pages:** Push to a GitHub repo and enable Pages in settings

---

## Screenshots

| Desktop | Tablet | Mobile |
|---------|--------|--------|
| *Desktop* <img width="1082" height="525" alt="Davivy Perfumes - Desktop" src="https://github.com/user-attachments/assets/ce5e0508-b734-496e-bad7-b5adf8ecc68a" />
|*Tablet* <img width="794" height="546" alt="Davivy Perfumes - Tablet" src="https://github.com/user-attachments/assets/145e8dca-f891-43ca-bacb-5c159b4267cb" />
|*Mobile* <img width="402" height="546" alt="Davivy Perfumes - Mobile" src="https://github.com/user-attachments/assets/6462a26b-c440-45f5-970f-894ab1e9bdfd" />
|
---

## Key Decisions

1. **Mobile-First Approach**  
   The CSS was written with a mobile-first mindset, using `min-width` media queries to progressively enhance the layout for larger screens. This ensures fast loading and good usability on all devices.

2. **CSS Custom Properties (Variables)**  
   All colors, fonts, and spacing values are defined as CSS variables in `:root`. This makes the design system easy to maintain and update globally.

3. **No External Frameworks**  
   The project uses pure HTML, CSS, and JavaScript without Bootstrap, Tailwind, or jQuery. This demonstrates core frontend fundamentals and keeps the bundle size minimal.

4. **Intersection Observer for Animations**  
   Instead of scroll-event listeners (which hurt performance), the `IntersectionObserver` API is used to trigger fade-in animations. This is more performant and battery-friendly.

5. **SVG Icons Over Icon Fonts**  
   All icons are inline SVGs. This avoids extra HTTP requests, ensures crisp rendering at any size, and eliminates dependencies on external icon libraries like Font Awesome.

6. **Semantic HTML**  
   The page uses proper semantic tags (`header`, `nav`, `section`, `footer`, `article`) for better accessibility and SEO.

---

## License

This project was built for educational purposes as part of a Frontend Developer Internship task.

---

**Built with passion by David Ibekwe**
