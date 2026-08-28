# tinyoak-landing

Static pages for thetinyoak.com, deployable on Cloudflare (Pages or Workers assets).

## /brand

`brand/index.html` — the Tiny Oak brand guidelines page (story, logo, colour,
the LIGHT framework, typography, voice). Pure static HTML: no build step. It
references the real logo assets in `/logos/` and Google Fonts.

Served at `/brand` when this directory is the site root. Link it from the main
landing page.

Assets:
- `logos/tinyoak-horizontal.svg` — horizontal lockup (mark + wordmark)
- `logos/tinyoak-mark.svg` — mark only
- `favicon.svg`

The brand system mirrors the app tokens (`src/v2/theme/tokens.css` in the
cadence repo): brand `#6321A9`, warm-stone neutrals, Barlow Condensed / Roboto /
IBM Plex Mono.
