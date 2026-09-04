# BottleTrack Landing Page

Static landing page for **BottleTrack**, the bottled beverage transport tracking and IoT monitoring platform built by **CodeCrafters**.

Course: 1ASI0730 Aplicaciones Web · Universidad Peruana de Ciencias Aplicadas.

## Stack

- HTML5, CSS3 and vanilla JavaScript. No build step and no frameworks.
- Design system implemented with CSS custom properties.
- Internationalization for `en-US` and `es-419`, with English as the default language.
- Accessibility following WAI-ARIA practices.

## Structure

```
index.html              home page
terms-of-service.html   terms and conditions, linked from the footer
style-guide.html        living documentation of the design system
assets/
  css/
    tokens.css          design tokens: color, typography, spacing, radius, elevation
    base.css            reset, element defaults and layout utilities
    components.css      shared components: button, card, chip, input, skip link
    layout.css          site header, navigation and footer
    landing.css         home page sections
    legal.css           terms and conditions page
    style-guide.css     style guide page
  js/
    translations.js     English and Spanish dictionaries
    i18n.js             language resolution, switching and persistence
    main.js             responsive navigation
    style-guide.js      copy to clipboard for color tokens
```

## Running locally

Open `index.html` directly in a browser, or serve the folder with any static server.

## Deployment

Published on GitHub Pages from the `main` branch.

The calls to action of each target segment point to the web application deployed on Vercel. The base URL lives in the `href` of those links in `index.html` and must be updated once the final domain is known.

## Conventions

- **GitFlow**: `main` holds released versions, `develop` integrates work, and every feature lives in its own `feature/<kebab-case-name>` branch.
- **Conventional Commits** for every commit message.
- **Semantic Versioning** for every release, tagged from a `release/<version>` branch.

## Team

CodeCrafters — Universidad Peruana de Ciencias Aplicadas.
