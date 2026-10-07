# Chandra Shekar — Full-Stack Developer Portfolio

A responsive personal portfolio website built with semantic HTML5 and custom CSS. The site presents Chandra Shekar's profile, technical skills, education, full-stack projects, and contact/social links in a polished single-page experience.

## Live Repository

- GitHub: https://github.com/Chandrashekar1404/ChandraShekar_Portfolio
- LinkedIn: https://www.linkedin.com/in/chandra-shekar-malthumkar-745534232/
- GitHub Profile: https://github.com/Chandrashekar1404

## Overview

This project is a lightweight, dependency-minimal portfolio website. It does not use a JavaScript framework or a package manager; the main application is rendered from `index.html` and styled through `Pf.css`.

The current version focuses on:

- A clean hero/profile section
- Sticky navigation with anchor-based section navigation
- About Me section
- Full-stack technical skills grouped into Frontend, Backend, and Database & Tools
- Education section
- Project showcase with GitHub links
- Contact/social section
- Floating decorative symbols and technology icons
- Hover transitions and section/card animations
- Responsive layouts for desktop, tablet, and mobile
- A fixed Back-to-Top button that remains hidden until the user scrolls

## Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Page structure and semantic content |
| CSS3 | Layout, responsiveness, animations, hover effects and visual design |
| Bootstrap 5.3.5 | Utility classes, buttons, grid/layout helpers |
| Devicon | Technology logos/icons |
| Google Fonts — Poppins | Typography |
| SVG | Social icons and inline vector graphics |
| JavaScript | Small interaction for smooth Back-to-Top behavior |

No React, Vite, Node.js, Spring Boot, Django, or database is required to run the portfolio itself.

## Project Structure

```text
ChandraShekar_Portfolio/
├── index.html
├── Pf.css
├── assets/
│   ├── myimg.jpg
│   ├── e-commerce.png
│   ├── bankmanage.jpg
│   ├── chat application.png
│   ├── expense.png
│   ├── expensetracker.png
│   └── wheathertrack.jpg
└── README.md
```

## Page Sections

### 1. Navigation

The top navigation provides anchor links to:

- Home
- About
- Skills
- Education
- Projects
- Contact

The navbar is sticky so it remains accessible while scrolling.

### 2. Hero / Home

The hero introduces Chandra Shekar as a full-stack developer and includes:

- Personal name
- Short professional tagline
- Learn More CTA
- Profile image
- Subtle floating visual effects

### 3. About

The About section communicates a full-stack development focus spanning Java, Spring Boot, React, Django, REST APIs, and MySQL, along with an interest in real-world projects, training and workshops.

### 4. Technical Skills

Skills are organized into three visual cards:

**Frontend**
- HTML
- CSS
- JavaScript
- React.js
- Tailwind CSS
- Bootstrap

**Backend**
- Java
- Spring Boot
- Python
- Django
- REST APIs
- JWT Authentication

**Database & Tools**
- MySQL
- PostgreSQL
- Git
- GitHub
- Docker
- AWS

The section uses technology icons, pill-style skill tags, hover effects, card elevation, and entrance animations.

### 5. Education

The current education entry highlights:

- 2024
- B.Tech — Electronics and Communication Engineering
- TKR College of Engineering and Technology

### 6. Projects

The portfolio showcases six projects:

1. **MegaVault — AI-Powered E-Commerce**
   - React
   - Spring Boot
   - MySQL
   - Spring Security
   - JWT
   - Razorpay

2. **Job Portal**
   - Full-stack job portal project
   - Repository: https://github.com/Chandrashekar1404/job-portal-fullstack

3. **AI Resume Builder**
   - React
   - Vite
   - JavaScript
   - Repository: https://github.com/Chandrashekar1404/AI-Resume-Builder-fullstack

4. **SafeBank — Full-Stack Banking**
   - React
   - Spring Boot
   - MySQL
   - Spring Security
   - JWT
   - Google OAuth
   - Gmail SMTP

5. **NexaDine — Restaurant & Food Ordering**
   - Full-stack restaurant/food ordering project
   - Repository: https://github.com/Chandrashekar1404/restaurant-fullstack

6. **Lumiora — AI Education Operating System**
   - AI-focused institute/education management platform
   - Repository: https://github.com/Chandrashekar1404/lumiora

Each project is presented as a responsive card with an image, summary and GitHub link.

## Visual Design

The current design uses a soft, modern white/light-lavender visual language with a blue-violet accent.

Key UI patterns include:

- Rounded cards
- Soft borders and shadows
- Gradient backgrounds
- Hover elevation
- Animated skill cards
- Technology-logo pills
- Decorative floating flower/symbol layer
- Floating technology-icon layer
- Responsive project grid
- Sticky navbar
- Fixed Back-to-Top control

The CSS also contains reduced-motion handling using `prefers-reduced-motion` for decorative animations.

## Responsive Behavior

The layout adapts across screen sizes:

- Desktop: multi-column skill and project grids
- Medium screens: project grid reduces from three columns to two
- Mobile: skills and projects collapse into single-column layouts
- Contact items wrap into a flexible layout
- Back-to-Top control scales down on smaller screens

## How to Run Locally

Because this is a static website, no build command is needed.

### Option 1 — Open directly

Clone the repository and open `index.html` in a browser.

```bash
git clone https://github.com/Chandrashekar1404/ChandraShekar_Portfolio.git
cd ChandraShekar_Portfolio
```

Then open `index.html`.

### Option 2 — VS Code Live Server

1. Open the repository in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

Using a local server is recommended when iterating on the page because it makes browser testing and refreshes easier.

## Deployment

The project is compatible with static hosting platforms such as:

- GitHub Pages
- Vercel
- Netlify

For GitHub Pages, publish the `main` branch and use the repository root as the site source.

For Vercel or Netlify, import the repository as a static site. No build command is required.

## Customization Guide

### Update Personal Information

Edit the hero, About, Education and Contact sections in `index.html`.

### Update Skills

Modify the three `.skill-card` groups and their `.skill-tags` in `index.html`.

### Add a New Project

Copy an existing project card inside `.cards2`, update:

- Project title
- Image
- Description
- Stack
- GitHub URL

Then add the image under `assets/`.

### Change Theme

The main accent and visual system are controlled by CSS variables and reusable styles in `Pf.css`. Update the accent values, shadows, gradients and card backgrounds centrally rather than editing every component individually.

## Accessibility Considerations

The current implementation includes:

- `alt` text for the profile image
- ARIA label on the Back-to-Top button
- `aria-hidden="true"` for decorative floating layers
- Keyboard focus styling for interactive controls
- `prefers-reduced-motion` support for decorative animations

## Development History

Recent refinements visible in the repository include:

- Reworking the portfolio project grid spacing
- Improving skill-card spacing
- Polishing the navigation and section styling
- Adding animated floating technology icons
- Adding subtle floating decorative symbols
- Fixing navbar stacking while scrolling
- Adding a fixed Back-to-Top button
- Making the Back-to-Top button appear only after scrolling
- Enabling smooth scroll-to-top behavior

## Future Enhancements

Potential next improvements:

- Add a downloadable resume button
- Add a dedicated experience section
- Add project live-demo links
- Add a functional contact form
- Add a dark mode
- Add project filtering by technology
- Move repeated content into structured JavaScript data
- Improve SEO metadata and social preview cards
- Compress large image assets for faster loading
- Add automated accessibility and Lighthouse checks
- Add CI/CD validation for HTML/CSS

## License

This project is a personal portfolio website. Unless otherwise stated in individual assets or linked projects, the source is intended for personal portfolio use by the author.

## Author

**Chandra Shekar**

Full-Stack Developer | Java | Spring Boot | React | Django | MySQL

- GitHub: https://github.com/Chandrashekar1404
- LinkedIn: https://www.linkedin.com/in/chandra-shekar-malthumkar-745534232/
