# Business Landing Page Template

A modern, production-ready **HTML/CSS business landing page template** with a dark theme and 2026 design trends. Built with pure HTML + CSS (Flexbox & Grid) — no frameworks or build tools required.

![Preview](https://img.shields.io/badge/Status-Ready-success?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

## ✨ Features

- **Hero Section** — Full-screen hero with animated stats and CTA buttons
- **Features Grid** — 6 feature cards with hover effects and gradient accents
- **CSS-only Testimonials Carousel** — Pure CSS slider (no JavaScript), 3 testimonial slides
- **Pricing Cards** — 3 tiers (Starter, Professional, Enterprise) with a featured "Most Popular" card
- **Contact Form** — Functional form with name, email, subject dropdown, and message field
- **Footer** — 4-column footer with links, social icons, and copyright
- **Dark Theme** — Modern dark color scheme with purple/indigo accent gradients
- **Responsive** — Fully responsive across desktop, tablet, and mobile
- **Smooth Animations** — Scroll-reveal fade-in animations and micro-interactions
- **Font Awesome Icons** — CDN-based icon library included
- **Mobile Navigation** — Hamburger toggle with smooth open/close

## 📸 Sections Included

| Section       | Description                                       |
| ------------- | ------------------------------------------------- |
| Navigation    | Fixed top nav with smooth scroll links + CTA btn |
| Hero          | Full-screen intro with badge, heading, stats      |
| Features      | 6-card responsive grid with hover effects         |
| Testimonials  | CSS-only carousel with 3 customer reviews         |
| Pricing       | 3-tier pricing table with featured card           |
| Contact       | 2-column layout: info details + contact form      |
| Footer        | Brand info, product/company/legal links, socials  |

## 🚀 Quick Start

1. **Download or clone** this repository
2. Open `index.html` in your browser to preview
3. Customize the content (see customization guide below)

No build steps, no npm install — just open and go!

## 🎨 Customization Guide

### Changing Colors

Edit the CSS custom properties in the `:root` block (around line 26 in `index.html`):

```css
:root {
  --accent: #7c3aed;           /* Primary accent (purple) */
  --accent-hover: #8b5cf6;     /* Hover state */
  --gradient-1: linear-gradient(135deg, #7c3aed, #4f46e5);  /* Primary gradient */
  --gradient-2: linear-gradient(135deg, #7c3aed, #ec4899);  /* Secondary gradient */
  --bg-primary: #0a0a0f;       /* Main background */
  --bg-secondary: #12121a;     /* Section backgrounds */
  --bg-card: #1a1a26;          /* Card backgrounds */
  --text-primary: #f0f0f5;     /* Main text */
  --text-secondary: #a0a0b8;   /* Secondary text */
}
```

### Changing Content

- **Logo/Company name** — Edit the `.logo` text in the `<nav>`, `<footer>`, and hero heading
- **Hero text** — Look for the `<h1>` and `<p>` in the `.hero` section
- **Features** — Each `.feature-card` block contains an icon, title, and description
- **Testimonials** — Each `.carousel-slide` contains review text and author info
- **Pricing** — Each `.pricing-card` has title, price, features list, and CTA button
- **Contact info** — Edit the email, phone, and address in the `.contact-detail` blocks

### Adding More Testimonial Slides

1. Add a new `<input type="radio">` with a unique ID (e.g., `slide-4`)
2. Add a new `.carousel-slide` inside `.carousel-track`
3. Add a corresponding `<label>` in `.carousel-controls`
4. Update the carousel transform: `#slide-4:checked ~ .carousel .carousel-track { transform: translateX(-300%); }`

### Replacing Social Links

Update the `href` attributes on the social icon links in the footer:
```html
<a href="https://twitter.com/yourhandle" aria-label="Twitter">...</a>
```

## 💰 Support

If you find this template valuable, consider supporting future development:

**[☕ Donate via PayPal](https://paypal.me/quisware/5)**

Your support helps create more high-quality, free templates and resources.

## 📄 License

MIT — free to use, modify, and distribute for personal or commercial projects.

---

Built with ❤️ using pure HTML, CSS, and Font Awesome.
