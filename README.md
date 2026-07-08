# ChessMastery Hub
Hosted demo: https://kb-akdm.github.io/ChessMastery-Hub/

A simple static website for ChessMastery Hub — a frontend prototype showcasing course listings, informational pages, and a combined sign-in / sign-up form.

## What this project contains

- `index.html` — Landing page with hero, courses section (`#ccs`), and footer.
- `aboutus.html` — About Us page.
- `contact.html` — Contact page with a contact form (static).
- `faq.html` — Frequently Asked Questions with expand/collapse behavior.
- `privacy.html` — Privacy Policy page.
- `signINnUP.html` — Combined Sign In / Sign Up page (tabs).
- `styles.css` — Global stylesheet used across pages.

## Features

- Consistent theme: dark-blue header (`#47617b`) with yellow accents (`#ffc107`).
- Navigation and footer link mapping between pages.
- Sign Up buttons open the sign-up tab directly using `?mode=signup` URL parameter.
- Course "Learn More" and "Browse Courses" CTAs jump to the `#ccs` section on `index.html`.

## Run / Preview

This is a static site — no build step required. To preview locally:

1. Open the project folder in your file manager.
2. Double-click `index.html` to open it in your browser.

Alternatively, serve it with a simple static server (recommended for testing links):

- Using Python 3:

```bash
cd "c:\Users\keyab\Downloads\Coding Projects\Chess App"
python -m http.server 8000
# then open http://localhost:8000 in your browser
```


## Editing notes

- Headings use the `h` class (defined in `styles.css`) to match the large hero font.
- Navbar buttons link to `signINnUP.html` (Sign In) and `signINnUP.html?mode=signup` (Sign Up).
- To change the site-wide footer style, edit `.foot` in `styles.css` and update footer HTML in each page if necessary.
- The Sign In / Sign Up page contains a small script that reads `?mode=signup` and opens the Sign Up tab automatically.

## Next steps you may want

- Add a build pipeline (Gulp/webpack) if you plan to expand.
- Replace placeholder content and images with real assets.
- Connect forms to a backend or a service (e.g., Firebase, Netlify Forms).

---

Created on: July 7, 2026

## Developer

- **Environment:** This is a static HTML/CSS prototype. No backend is included.
- **Local dev server:** Use `python -m http.server 8000` from the project root to serve pages locally.
- **Code style:** HTML uses Bootstrap 5 for layout. Keep styling in `styles.css`. Use semantic HTML where possible.
- **Contributing:** Fork the project, make changes on a branch, and submit a pull request. Keep changes focused and avoid unrelated reformatting.
- **Testing:** Manually verify links and forms by running the local server and clicking through pages. Use browser devtools to inspect layout and responsive breakpoints.
- **Build / tooling suggestions:** Add a linter (HTMLHint), CSS preprocessor (Sass), and an optional bundler if you expand the project.
- **Developer contact:**
	- Name: Keya
	- Country: USA
	- Grade: 7

