# AI Fest 2026 - College Event Landing Page
**Instructor:** Senior Frontend Developer & Tech Educator (10+ Years Experience)  
**Objective:** Build a responsive, accessible, and modern single-page web application using HTML5 and Bootstrap 5.

---

## 📋 Table of Contents
1. [Project Overview](#project-overview)
2. [Tech Stack & Assets](#tech-stack--assets)
3. [Step-by-Step Architectural Breakdown](#step-by-step-architectural-breakdown)
4. [Full Source Code](#full-source-code)
5. [Instructor Pro-Tips for Students](#instructor-pro-tips-for-students)

---

## 1. Project Overview
This project simulates a real-world conference/event landing page. A great event page must meet three key criteria:
- **Clarity:** Users should know *what*, *when*, and *where* within 3 seconds of landing.
- **Responsiveness:** Flawless rendering on mobile devices, tablets, and large desktop monitors.
- **Conversion-Driven:** Clear CTAs (Calls to Action) like "Register Now" leading directly to the registration section.

---

## 2. Tech Stack & Assets
- **HTML5:** Semantic markup (`<header>`, `<nav>`, `<section>`, `<footer>`).
- **Bootstrap 5.3:** Utility-first CSS framework for grid layouts, typography, tables, buttons, and cards.
- **Bootstrap Icons:** Lightweight vector icon library (`bi bi-*`).
- **Unsplash:** High-quality placeholder photography for background imagery and speaker headshots.

---

## 3. Step-by-Step Architectural Breakdown

### Section 1: Header (Navbar)
- Built using `.navbar`, `.navbar-expand-lg`, and `.fixed-top` so the navigation bar stays pinned at the top while scrolling.
- Includes a smooth brand title and navigational anchor links that correspond to section IDs.

### Section 2: Hero / Banner
- Features a dark gradient overlay combined with a background cover image using custom inline/internal CSS.
- Displays core event metadata (Date, Time, Venue) with Bootstrap icons and a prominent primary action button.

### Section 3: About Event
- Uses Bootstrap's 12-column grid (`.row` and `.col-lg-6`) to create a clean two-column layout (text description on the left, visual image on the right).
- Integrates quick statistical counter icons to highlight event scale.

### Section 4: Schedule Table
- Uses `.table-responsive` to prevent horizontal overflow breakage on mobile devices.
- Styled with `.table-striped` and `.table-hover` for clean readability.

### Section 5: Speakers / Guests
- Powered by Bootstrap Cards (`.card`, `.card-img-top`, `.card-body`) arranged in a 3-column grid (`.col-md-4`).
- Leverages Flexbox utilities (`.d-flex`, `.flex-column`, `.flex-grow-1`) to ensure uniform card heights regardless of text length.

### Section 6: Registration Form
- Centered container layout for focus.
- Includes standard input elements (`text`, `email`) and a `<select>` dropdown for session selection, all styled with `.form-control` and `.form-select`.

### Section 7: Footer
- Dark background (`.bg-dark`) with centered social media links and copyright notice.

---

## 5. Instructor Pro-Tips for Students
1. **Semantic HTML:** Always use semantic elements (`<header>`, `<section>`, `<footer>`) instead of generic `<div>` tags where possible. This boosts SEO and screen-reader accessibility.
2. **Mobile First:** Always test your layouts on mobile viewports using your browser's Developer Tools (`F12`). Bootstrap classes like `col-md-4` automatically stack items on mobile and place them side-by-side on medium/large screens.
3. **Accessibility:** Ensure every `<img>` tag has a descriptive `alt` attribute, and form inputs are correctly paired with `<label>` tags.
4.