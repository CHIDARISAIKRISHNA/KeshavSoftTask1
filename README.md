# CSK — Bootstrap 5 UI Project

A responsive multi-page website built for the **Bootstrap 5 Internship Task** at Keshavsoft. Three pages created by remixing official Bootstrap 5 component.
---

## Live Demo

| | URL |
|---|-----|
| **GitHub Repository** | `https://github.com/CHIDARISAIKRISHNA/KeshavSoftTask1` |
| **Live Preview** | `https://yourusername.github.io/Bootstrap_Keshavsoft` |

> Replace `yourusername` with your actual GitHub username after deploying.

---

## Project Overview

This project demonstrates hands-on use of **Bootstrap 5** to build a clean, modern, and fully responsive website. Each page combines multiple Bootstrap components with custom CSS for a polished look.

### Design Theme

| Element | Style |
|---------|-------|
| Navbar | Dark charcoal (`#1a1a2e`) |
| Footer | Dark gradient (`#1a1a2e` → `#0f0f1a`) |
| Hero / Page headers | Blue → purple gradient |
| Content sections | Light background with card-based layout |

---

## Pages & Components

### Home — `index.html`

| Section | Bootstrap Components |
|---------|-------------------|
| Navbar | Responsive navbar with collapse toggler |
| Hero | Full-width hero with image, badge, and CTA buttons |
| Features | 3 feature cards with Bootstrap Icons |
| Testimonials | **Carousel** with indicators and prev/next controls |
| Services | Image cards with buttons |
| CTA Banner | Call-to-action section |
| Footer | Links, social icons, copyright |

### About — `about.html`

| Section | Bootstrap Components |
|---------|-------------------|
| Navbar | Same responsive navbar |
| Page Hero | Centered hero banner |
| Who We Are | Two-column grid with image |
| Mission & Vision | Side-by-side cards |
| Why Choose Us | 3 feature cards |
| Team | Team member cards with images |
| Statistics | Stats counter row |
| CTA + Footer | Contact prompt and footer |

### Contact — `contact.html`

| Section | Bootstrap Components |
|---------|-------------------|
| Navbar | Same responsive navbar |
| Page Hero | Centered hero banner |
| Contact Form | Bootstrap form with validation |
| Contact Info | Info cards (address, email, phone, hours) |
| Google Map | Embedded map (`ratio-16x9`) |
| FAQ | **Accordion** component |
| Success **Modal** | Shown after valid form submission |
| Footer | Same footer as other pages |

---

## Bootstrap Components Checklist

| Component | Used | Page |
|-----------|------|------|
| Navbar | ✅ | All pages |
| Hero | ✅ | Home, About, Contact |
| Cards | ✅ | All pages |
| Carousel | ✅ | Home (testimonials) |
| Forms | ✅ | Contact |
| Modal | ✅ | Contact |
| Accordion | ✅ | Contact (FAQ) |
| Grid System | ✅ | All pages |
| Utility Classes | ✅ | All pages |
| Bootstrap Icons | ✅ | All pages |

---

## Tech Stack

- **HTML5** — semantic page structure
- **CSS3** — custom styling in `css/style.css`
- **Bootstrap 5.3.7** — via CDN
- **Bootstrap Icons 1.11.3** — via CDN
- **Google Fonts (Inter)** — typography
- **Vanilla JavaScript** — `js/script.js`

---

## File Structure

```
Bootstrap_Keshavsoft/
├── index.html          # Home page
├── about.html          # About / Services page
├── contact.html        # Contact page with form
├── css/
│   └── style.css       # Custom styles & design tokens
├── js/
│   └── script.js       # Navbar scroll + form validation
└── README.md           # This file
```

---

## How to Run Locally

1. Download or clone this project folder
2. Open `index.html` in any modern browser (Chrome, Firefox, Edge)
3. Navigate between pages using the navbar — no build step or server required

---

## Deploy to GitHub Pages

1. Create a new repository on GitHub
2. Push all project files to the `main` branch:

```bash
git init
git add .
git commit -m "Bootstrap 5 internship project"
git branch -M main
git remote add origin https://github.com/yourusername/Bootstrap_Keshavsoft.git
git push -u origin main
```

3. Go to **Repository → Settings → Pages**
4. Under **Source**, select **Deploy from branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save** — your site will be live at:
   `https://yourusername.github.io/Bootstrap_Keshavsoft`

### Alternative: Netlify

1. Go to [netlify.com](https://www.netlify.com)
2. Drag and drop the project folder
3. Your site gets a live URL instantly (e.g. `yourproject.netlify.app`)

---

## JavaScript Features

| Feature | File | Description |
|---------|------|-------------|
| Navbar scroll effect | `script.js` | Adds `scrolled` class when user scrolls down |
| Form validation | `script.js` | Bootstrap `was-validated` on invalid submit |
| Success modal | `script.js` | Shows confirmation modal after valid form submit |

---

## Project Reflection

> **Note:** This section is mandatory for internship submission. Fill in the personal parts honestly before submitting.

### Step-by-Step Process

1. **Explored Bootstrap 5 documentation and examples** — studied Navbar, Cards, Carousel, Grid, Forms, Accordion, and Modal from [getbootstrap.com](https://getbootstrap.com) and the official Examples section.
2. **Planned the page structure** — Home (hero, features, carousel, services), About (company info, mission, team, stats), Contact (form, map, FAQ).
3. **Built HTML skeleton** — linked Bootstrap 5 and Bootstrap Icons via CDN, used the grid system and utility classes.
4. **Designed custom CSS** — created a design system with CSS variables, dark navbar/footer, blue gradient heroes, card hover effects, and responsive typography.
5. **Added JavaScript** — navbar scroll behavior, contact form validation, and success modal.
6. **Tested responsiveness** — checked layout on desktop, tablet, and mobile screen sizes.

### Tools & Resources Used

| Resource | How It Was Used |
|----------|-----------------|
| [Bootstrap 5 Docs](https://getbootstrap.com/docs/5.3/getting-started/introduction/) | Component structure, utility classes, grid system |
| [Bootstrap Examples](https://getbootstrap.com/docs/5.3/examples/) | Inspiration for Navbar, Cards, Hero, Carousel, Accordion |
| Bootstrap Icons | Icons for features, contact info, social links |
| Google Fonts (Inter) | Custom typography |
| Unsplash / RandomUser.me | Placeholder images for hero, services, team, carousel |
| ChatGPT / other AI  |

### Challenges & Solutions

| Challenge | Solution |
|-----------|----------|
| Keeping design consistent across 3 pages | Shared CSS variables (`--navbar-bg`, `--hero-bg`, `--gradient`) and reusable classes (`feature-card`, `page-hero`, `section-header`) |
| Contact form working without a backend | Bootstrap client-side validation + JavaScript modal on successful submit |
| Navbar and hero color coordination | Dark solid navbar (`#1a1a2e`) with blue gradient hero sections below |
| Responsive layout on mobile | Bootstrap `col-*` grid classes + custom media queries in `style.css` |
| Carousel styling to match site theme | Custom CSS for testimonial cards, circular controls, and dot indicators |

### Learning Journey

*(Write 2–3 paragraphs in your own words. Example topics: what you learned about Bootstrap grid, how you remixed components, responsive design, CSS customization, etc.)*

### Time Taken

| Phase | Duration |
|-------|----------|
| Research & planning | 0.5 hours |
| HTML structure | 15 minutes |
| CSS styling | 0.5 hours |
| JavaScript & testing | 15 minutes |
| Deployment | 10 minutes |
| **Total** | ** 1 hours / 45 minutes** |

---

## Submission Checklist

- [ ] All 3 pages complete (`index.html`, `about.html`, `contact.html`)
- [ ] Bootstrap 5 loaded via CDN
- [ ] Responsive on desktop, tablet, and mobile
- [ ] Contact form validates and shows modal
- [ ] Code pushed to GitHub
- [ ] Deployed on GitHub Pages or Netlify
- [ ] Live URL added above
- [ ] Reflection section completed with your name and time taken

---
