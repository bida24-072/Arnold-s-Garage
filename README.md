# 🏁 Arnold's Garage — README

A responsive, dark-themed single-page website showcasing **Muscle**, **Luxury**, **Off-Road**, and **Racing** cars. Built with pure HTML5 and CSS3 — no external libraries, fonts, or images required.

---

## 📖 Overview

**Arnold's Garage** is a static, self-contained website designed as a template for a car dealership, garage, or enthusiast showcase. It follows **W3Schools layout principles** — clean grid structures, rounded cards, clear navigation, and mobile-first responsiveness.

The site uses a **"garage" aesthetic**: deep blacks, metallic greys, and a signature gold accent (`#c9a03d`) to convey power, luxury, and craftsmanship.

---

## ✨ Features

| Feature | Description |
|---|---|
| **4 Car Categories** | Muscle, Luxury, Off-Road, and Racing — each with 3 representative models. |
| **W3Schools-Style Layout** | Max-width container, card grid, rounded corners, clear section titles. |
| **Dark Garage Theme** | Black background, gold accents, subtle gradients, and drop shadows. |
| **Responsive Design** | Adapts seamlessly from desktop → tablet → mobile using Flexbox & CSS Grid. |
| **Interactive Navigation** | Navbar with hover effects and an active state indicator. |
| **Hover Animations** | Car cards lift up and gain a gold border on hover. |
| **Zero External Dependencies** | No images, no fonts, no JS libraries — 100% self-contained HTML + CSS. |
| **Embedded README** | A styled "README" section is included directly inside the webpage. |

---

## 🛠️ Technologies Used

- **HTML5** — semantic structure (`<header>`, `<nav>`, `<section>`, `<article>`)
- **CSS3** — Flexbox, CSS Grid, media queries, gradients, transitions, `box-shadow`
- **W3Schools Layout Principles** — container centering, padding, card style, responsive breakpoints

---

## 📂 File Structure

```
arnolds-garage/
│
├── index.html          # Main website file (HTML + embedded CSS)
└── README.md           # This file
```

> 💡 The entire website is contained in a **single HTML file**. You can rename it to `index.html` for web hosting.

---

## 🚀 Getting Started

### 1. View Locally

Simply **double-click** the `index.html` file, or open it in any modern browser:

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Safari

No build tools, servers, or installs required.

### 2. Deploy Online

Upload `index.html` to any static hosting service:

- **GitHub Pages** — push to a repo and enable Pages in settings.
- **Netlify / Vercel** — drag-and-drop the file.
- **Any web host** — upload via FTP to your public folder.

---

## 🎨 Customization Guide

### Change Car Models & Specs

Locate the `.car-card` blocks inside each section (MUSCLE, LUXURY, OFF-ROAD, RACING) and edit:

```html
<h3>Your Car Name</h3>
<div class="sub">Engine Specs</div>
<p>Short description of the car.</p>
<div class="specs">
    <span><i>⚡</i> 0-60: X.Xs</span>
    <span><i>🏁</i> Top Speed</span>
    <span><i>⚙️</i> Transmission</span>
</div>
```

### Add Real Car Images

Replace the CSS gradient backgrounds with real photos by editing the `.car-image` classes:

```css
.muscle-bg {
    background-image: url('images/challenger.jpg');
    background-size: cover;
    background-position: center;
}
```

Then update the HTML:

```html
<div class="car-image muscle-bg" style="background-image: url('images/challenger.jpg');">
    <span class="car-tag">MUSCLE</span>
</div>
```

### Change the Theme Color

Find and replace the gold accent value `#c9a03d` throughout the CSS with your preferred color.

### Add More Cars

Copy any existing `.car-card` block and paste it inside the relevant `.car-grid`. The grid will automatically accommodate the new card.

### Enable Navigation Links

Currently the nav links are placeholders. To make them functional anchors, add `id` attributes to each section and update the `href`:

```html
<!-- In navbar -->
<li><a href="#muscle">MUSCLE</a></li>

<!-- On the section -->
<h2 class="section-title" id="muscle">...</h2>
```

---

## 📱 Responsive Breakpoints

| Breakpoint | Behavior |
|---|---|
| **> 768px** | Multi-column grid (auto-fit, min 280px per card) |
| **≤ 768px** | Single-column grid, smaller fonts, compact navbar |
| **≤ 480px** | Stacked header, full-width hero, minimal padding |

---

## 🧩 Browser Support

| Browser | Supported |
|---|---|
| Chrome | ✅ Latest |
| Firefox | ✅ Latest |
| Edge | ✅ Latest |
| Safari | ✅ Latest |
| Opera | ✅ Latest |
| IE 11 | ❌ Not supported (uses CSS Grid) |

---

## 📝 Notes

- Car specifications are **illustrative** and based on real-world models for authenticity.
- The design is intentionally **single-page** — easy to split into multiple pages if needed.
- All visual effects (car backgrounds, tags, shadows) are achieved with **pure CSS** — no images required.
- The embedded README section at the bottom of the page can be removed if you prefer a cleaner layout.

---

## 🔮 Possible Enhancements

- [ ] Add anchor links for smooth scrolling navigation
- [ ] Integrate a contact form (requires backend or Formspree)
- [ ] Add a JavaScript filter to toggle car categories
- [ ] Replace gradients with real car photography
- [ ] Add a gallery/lightbox for each car
- [ ] Include pricing and "Enquire Now" buttons
- [ ] Split into multiple pages (Home, Muscle, Luxury, etc.)

---

## 📄 License

This project is free to use for **personal and commercial** purposes. Attribution is appreciated but not required.

---

## 🙌 Credits

- **Design & Code:** Arnold's Garage
- **Layout Inspiration:** [W3Schools](https://www.w3schools.com/)
- **Theme:** Dark garage / industrial luxury

---

## 📬 Contact

For questions, suggestions, or custom work:

- 📧 **Email:** hello@arnoldsgarage.example
- 🌐 **Website:** arnoldsgarage.example
- 📍 **Location:** 42 Piston Avenue, Motor City

---

> ⚡ **"Where horsepower meets passion."** ⚡
>
> © 2026 Arnold's Garage — Built with a love for machines.
