# ERIC ON ACID

A responsive, prebuilt static explainer website for the ERIC meme-token experiment. The site uses no framework, package manager, server-side runtime, analytics or live API.

## Preview locally

Open `index.html` in a browser, or serve this directory with any static file server. For example:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Build and deployment

There is no build step. Publish the repository root as static files with GitHub Pages or another static host. For a GitHub Pages preview, use repository **Settings → Pages**, select **Deploy from a branch**, choose `preview/initial-framework` and `/ (root)`, then save. This is an instruction only; Pages has not been enabled or deployed as part of this work.

## Content and data

The static page is complete without a runtime feed. A clearly marked WOA story panel is the cached/static fallback. The JavaScript contains a read-only integration seam whose endpoint is deliberately unset until a verified public WOA feed exists. No automatic/manual post-launch maintenance is needed for the static core.

The page distinguishes confirmed details from unknown deployment facts, including supply, decimals, mint address and trading pair. Rewards are conditional and not guaranteed. It makes no legal issuerless classification claim.

## Artwork and references

The hero uses the existing ERIC scrapyard artwork supplied in the WOA project assets. The page content follows `ERIC_on_Acid_Project_Explainer_v0.4.docx`; unknown values remain labelled as unconfirmed.
