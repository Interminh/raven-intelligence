# Raven Intelligence

A landing page concept for a AI hardware product, built to practice front-end design and animation. No frameworks, just HTML, CSS, and vanilla JS.

## About

Raven Intelligence is a design exercise, built for my peers who had a vision for a hardware product. The site is styled like a premium tech launch page (think Apple-style scroll reveals) to explore layout, motion, and typography choices in a polished, production-like setting.

## Features

- Scroll-triggered section reveals using the Intersection Observer API
- Two image carousels with arrow, dot, swipe, and drag navigation
- Responsive layout for desktop, tablet, and mobile
- Collapsible info cards with a typewriter text effect
- Custom slide-out side menu with section jump links

## Tech

- HTML5 / CSS3
- Vanilla JavaScript (no build tools or dependencies)
- Custom font (`Ravenfont.ttf`) plus Playfair Display and Montserrat from Google Fonts

## Running locally

This is a static site, so no build step is required. Clone the repo and open `index.html` in a browser, or serve it locally:

```bash
git clone https://github.com/Interminh/raven-intelligence.git
cd raven-intelligence
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

```
index.html      Markup and page scripts
index.css       Styles and responsive breakpoints
images/         Product renders and photos used on the site
Ravenfont.ttf   Custom display font
```

## Credits

Design and development by [Interminh](https://github.com/Interminh).
