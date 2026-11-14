# ARDA ÇEKMECE — THE ECONOMICS UNIVERSE

An original bilingual, interactive economics-themed portfolio. React + TypeScript + Vite; deploys as a static GitHub Pages site.

## Setup

```bash
npm ci
npm run dev
npm run build
```

## GitHub Pages deployment

1. Create a new GitHub repository, upload **the contents of this folder** (not the outer ZIP directory), and push to `main`.
2. Open **Settings → Pages → Build and deployment → Source: GitHub Actions**.
3. The included `.github/workflows/deploy.yml` installs dependencies, builds and publishes automatically.
4. For a user/org root site instead of a project repo, adjust `VITE_BASE_PATH` to `/` in the workflow.

## Authorized portrait

The authorized image was shown in the chat but no image file was mounted in this build environment. Therefore no photo has been falsely claimed to be included. Put the authorized image at `public/portrait.jpg`; the site automatically uses it, falling back to `public/portrait-placeholder.svg` until then.

## Verification and editorial notes

Facts drawn from Arda's public LinkedIn profile (reviewed November 2026): LMU Munich (2025–present), listed economics courses, WASTI e.V. affiliation (role not public in retrieved snippet), ijgd environmental volunteering in Wolfsburg (Jul–Aug 2024), and language/certificate entries. Unclear dates, employers, titles and academic results were intentionally not invented. Confirm every public-facing fact with Arda before publishing. The economics lab uses **simulated** parameters and is not his research. No analytics, tracking or third-party submission endpoint is included.

Sources: https://de.linkedin.com/in/ardacekmece and https://de.linkedin.com/in/ardacekmece/en

## Content and configuration

All interface copy, sections and interactive code live in `src/main.tsx`. Change the LinkedIn URL in `LINKEDIN`. No API keys needed. External Google Fonts are optional; local serif/sans fallbacks are provided.
