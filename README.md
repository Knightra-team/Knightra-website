# Knightra Website

A responsive, dark, blue/purple software-team website inspired by the supplied visual reference.

## Included
- English-first, bilingual English/Persian UI
- Persian RTL support with `dir="rtl"`
- Language preference saved in localStorage
- Responsive navigation + mobile menu
- Home, About, Services, Projects, Team and Contact pages
- Dark neon-blue/purple visual system
- Placeholder areas for future logo, project case studies, contact details and team bios
- Static contact form demo with success message

## Run locally
Open `index.html` directly, or serve the folder with any static HTTP server.

Example:
```bash
python -m http.server 8080
```
Then open `http://localhost:8080`.

## Main files
- `index.html` — homepage
- `about.html` — team/company overview
- `services.html` — services
- `projects.html` — portfolio placeholders
- `team.html` — three team members
- `contact.html` — contact form
- `assets/styles.css` — full visual styling
- `assets/app.js` — translations, RTL handling, language switch and interactions
- `assets/icon.svg` — temporary logo/icon placeholder

## Before publishing
1. Replace the temporary K logo with the final Knightra logo.
2. Replace placeholder project content with real screenshots, links, tech stacks and results.
3. Add real email/location/contact details on the Contact page.
4. Connect the contact form to your backend or a form service.
