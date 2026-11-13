# ERIC ON ACID

The Eric On Acid website is a small, responsive, static site for Eric and the ERIC meme-token experiment. It is built with plain HTML, CSS and JavaScript; there is no application framework, analytics integration or runtime API.

## Site structure

- `index.html` — the main Eric page. It introduces Eric, links to his personal story, provides a downloadable Eric image for memes, and contains the token information, rewards explanation, risk disclosures and FAQ.
- `story.html` — Eric's personal history, **Before the Morning After**. It uses a one-section-at-a-time reader with previous/next navigation, a contents menu and saved reading position.

The story is presented as Eric's own account. The wider WORMS ON ACID creative universe is separate; this site does not reproduce the wider universe's stories or content.

## Assets and implementation

- `assets/` contains the site's artwork, logo and visual assets.
- The pages use plain HTML, CSS and JavaScript, with no build step or package installation required.
- Google Fonts are requested externally for the site's display, handwritten and monospace typography. The pages do not depend on an external runtime API.

## Token information and verification

Token details are shown only where they have been verified. Supply, decimals, launch status, mint address, trading destination, creator holdings and wallet details must remain marked as pending until confirmed. Do not replace pending details with estimates.

Holder rewards are conditional on activity, eligibility, available vault balances and the applicable Pump.fun programme rules. Distributions are not guaranteed. The site also includes risk disclosures and an FAQ; nothing on the site should be read as a promise of returns.

## Local preview

Open `index.html` in a browser to view the main page. Open `story.html` to view the story reader. Alternatively, serve the repository directory with any static file server.

## Public preview

GitHub Pages serves the static site from the `main` branch and repository root when Pages is enabled in repository settings.
