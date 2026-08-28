# tinyoak-landing

Static site for **thetinyoak.com**, deployable on Cloudflare Pages (no build step).

## Structure

- `index.html` — the landing page (imported from the current production site).
- `assets/` — landing assets: horizontal logo, the `tree-year-*.svg` growth
  illustrations, and `fonts.css` (Barlow Condensed / Roboto / IBM Plex Mono).
- `brand/index.html` — the Tiny Oak **brand guidelines** page, served at `/brand`
  (linked from the landing footer). Story, logo, colour, the LIGHT framework,
  typography and voice.
- `logos/` — `tinyoak-horizontal.svg`, `tinyoak-mark.svg` (used by the brand page).
- `favicon.svg`

## Deploy (Cloudflare Pages)

This repo is meant to be the Git source for the `tinyoak-landing` Pages project:
- **Production branch:** `main`
- **Build command:** none
- **Build output directory:** `/`

Every push to `main` redeploys. The custom domain `thetinyoak.com` already points
at the project (`thetinyoak.com CNAME -> tinyoak-landing.pages.dev`).

## Brand system

Brand `#6321A9` on white, ink `#1A1A1A`, deep violet `#1C0840`; Barlow Condensed
(display) / Roboto (body) / IBM Plex Mono (data) — matching the app tokens
(`src/v2/theme/tokens.css` in the cadence repo).
