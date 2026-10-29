# TransMove — Modern Transport & Fleet Mobility Website

A modern, responsive, and accessible transport company website designed for a university **Web Design & Development** assignment. Built using strictly **HTML5**, **CSS3**, and **Font Awesome icons**—with **no Bootstrap**, **no Tailwind**, and **no unnecessary JavaScript**.

---

## 📸 Design Inspiration & Reference Alignment

The design draws direct aesthetic, typographic, and layout inspiration from the provided reference image:
- **Clean Blue & White Palette**: Uses high-contrast navy (`#0b2545`, `#08244c`) and ice-blue (`#edf4fa`) with pure white.
- **Why Choose Us Section**: Recreates the dual-card structure from the reference:
  - **Left Card ("Our Services")**: Styled in ice-blue with a circular badge, navy heading, and clean spacing covering *Comfortable vehicles*, *Affordable pricing*, *Fast booking*, and *Professional drivers*.
  - **Right Card ("Why Choose Our Transport Company")**: Styled in deep midnight navy with white typography and circular badge covering *Safe travel*, *GPS tracking*, *24/7 availability*, *Experienced drivers*, and *Customer satisfaction*.
- **Editorial Typography**: Styled with Google Fonts (`Outfit` for crisp headings and `Plus Jakarta Sans` for clean, legible body text).

---

## 🚀 Key Features

1. **Dark Mode & Light Mode (Same Blue & White Foundation)**:
   - Built directly into CSS custom properties using `[data-theme="dark"]` and `@media (prefers-color-scheme: dark)`.
   - Uses the identical rich navy, royal blue, ice blue, and crisp white palette inverted seamlessly for night and daytime readability.
   - Interactive theme toggle button in the header with animated Sun/Moon icon transitions.
   - Saves preference in `localStorage` with zero-flash initial loading.

2. **Semantic HTML5 Architecture**:
   - Structured with `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>` tags.
   - Fully accessible with ARIA attributes, semantic headings (`h1` through `h4`), and descriptive `alt` tags.

3. **Zero-Dependency Pure CSS Mobile Navigation**:
   - Uses an accessible pure CSS checkbox toggle pattern (`#nav-toggle:checked ~ .nav-menu`).
   - Smoothly transforms the hamburger icon into an "X" with clean transitions on mobile viewports.

3. **Homepage Sections**:
   - **Header & Navigation**: Brand logo, navigation links, and a prominent "Book Now" CTA.
   - **Hero Section**: Catchy badge with live pulse indicator, large display heading, dual CTA buttons ("Book a Ride" & "Learn More"), trust statistics, and a custom vector transport illustration.
   - **Services Section**: 4 interactive service cards with hover lift animations and icons:
     - *City Transport*
     - *Airport Transfers*
     - *School Transport*
     - *Parcel Delivery*
   - **Why Choose Us (Dual Reference Cards)**: Clean comparison cards matching the reference image.
   - **Fleet Section**: 4 vehicle cards (*Executive Sedan*, *Luxury SUV*, *Executive Van*, *Charter Bus*) featuring passenger capacity, luggage tags, pricing ranges, and booking CTAs.
   - **Testimonials Section**: 3 customer reviews with 5-star rating badges and verified reviewer profiles.
   - **Contact Section**: Accessible booking and quote request form alongside corporate address details, phone hotline, email, and a styled live satellite map frame.
   - **Footer**: Brand summary, quick links, services directory, certification badges, social links, and copyright text.

4. **Modern CSS3 Techniques**:
   - CSS Custom Properties (`:root` variables) for effortless color and spacing theming.
   - CSS Grid and Flexbox layouts for robust multi-device alignments.
   - Micro-interactions, smooth hover elevations, and soft shadows.
   - Media queries ensuring responsive support across Desktop, Tablet, and Mobile.

---

## 📁 File Structure

```text
transport-company/
├── index.html          # Semantic HTML5 markup
├── style.css           # Pure CSS3 stylesheet with variables & media queries
├── README.md           # Documentation and assignment overview
└── images/             # Vector SVG assets
    ├── logo.svg
    ├── hero-transport.svg
    ├── sedan.svg
    ├── suv.svg
    ├── van.svg
    ├── bus.svg
    ├── avatar-1.svg
    ├── avatar-2.svg
    ├── avatar-3.svg
    └── map-placeholder.svg
```

---

## 💻 How to Run the Project

No build tools, Node.js, or package managers are required!

### Option 1: Direct Browser Launch
1. Navigate to the `transport-company/` directory.
2. Double-click `index.html` to open it in Google Chrome, Microsoft Edge, Mozilla Firefox, or Safari.

### Option 2: Local Web Server (VS Code / Python)
- **VS Code**: Right-click `index.html` and click **"Open with Live Server"**.
- **Python**: Run the following in your terminal inside the `transport-company` folder:
  ```bash
  python -m http.server 8000
  ```
  Then visit `http://localhost:8000` in your web browser.

---

## ♿ Accessibility & Standards Compliance

- **WCAG 2.1 AA / AAA Compliance**: High contrast ratios on all text elements and buttons.
- **Keyboard Friendly**: Visible `:focus-visible` outline rings for keyboard navigation.
- **Fast Performance**: Lightweight vector SVG graphics guarantee razor-sharp rendering on Retina/4K displays with near-instant load times.
