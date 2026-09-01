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
assets/
  css/
    tokens.css        design tokens: color, typography, spacing, radius, elevation
    base.css          reset, element defaults and layout utilities
    components.css    shared components: button, card, chip, input, skip link
    style-guide.css   styles specific to the style guide page
  js/
style-guide.html      living documentation of the design system
```

## Running locally

Open `style-guide.html` directly in a browser, or serve the folder with any static server.

## Deployment

Published on Netlify from the `main` branch.

## Conventions

- **GitFlow**: `main` holds released versions, `develop` integrates work, and every feature lives in its own `feature/<kebab-case-name>` branch.
- **Conventional Commits** for every commit message.
- **Semantic Versioning** for every release, tagged from a `release/<version>` branch.

## Team

CodeCrafters — Universidad Peruana de Ciencias Aplicadas.
