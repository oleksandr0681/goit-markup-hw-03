# goit-markup-hw-03

Homework assignment #3 from the [GoIT](https://goit.global/) HTML/CSS markup course. Building on homework #2, this task refactors the "Webstudio" landing page markup by introducing reusable `container` wrappers for consistent, responsive-ready page width and improving section/card structure and accessibility.

## 📋 About

The page is a styled business landing for a fictional web studio. Compared to the previous homework, this version:

- Wraps each section's content in a `.container` element for consistent horizontal padding/max-width.
- Groups the header's logo and navigation into a `.menu-box` wrapper.
- Wraps team and portfolio card content (`h3` + `p`) in a `.team-card-content` / `.project-card-content` div for cleaner card styling.
- Adds a `visually-hidden` class to the "Our Features" heading to keep it accessible to screen readers while hiding it visually.
- Adds dedicated list classes (`features-card-list`, `team-list`, `project-list`) for easier styling.

The page itself still includes:

- A header with a logo, main navigation (Studio / Portfolio / Contacts), and contact links (email and phone).
- A hero section with a heading and an "Order Service" button.
- An "Our Features" section listing four company strengths (Strategy, Punctuality, Diligence, Technologies).
- An "Our Team" section presenting four team members with photos, names, and roles.
- An "Our Portfolio" section showcasing six sample projects with images, titles, and categories (App, Marketing, Design).
- A footer with the logo and a short company tagline.

## 🛠️ Tech Stack

- HTML5 (semantic elements: `header`, `nav`, `main`, `section`, `address`, `footer`)
- CSS3 (custom styles in `css/styles.css`)
- [modern-normalize](https://github.com/sindresorhus/modern-normalize) (via CDN) for CSS resets
- Google Fonts (Raleway, Roboto)

## 📁 Project Structure

```
goit-markup-hw-03-main/
├── css/
│   └── styles.css    # Page styles
├── images/            # Team photos and portfolio project images
└── index.html          # Page markup
```

## 🚀 Getting Started

No build step or server required — just open `index.html` in a browser (an internet connection is needed to load the Google Fonts and the normalize.css CDN link).
