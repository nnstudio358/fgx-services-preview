# FGX Creative — 2026 Services (scroll preview)

A self-contained preview page. No build step, no server code: it is one HTML file plus images.

## Put it online in ~2 minutes (no GitHub needed)
1. Go to app.netlify.com/drop (or Cloudflare Pages → Create → Upload assets).
2. Drag this whole folder onto the page.
3. Copy the link it gives you and send it to the client.

## Or host it on GitHub Pages
1. Create a repo and upload these files at the root (index.html must be at the top level).
2. Settings → Pages → Source: "Deploy from a branch" → main → / (root).
3. The link appears in the same panel after a minute.

## Notes
- Best in Chrome, Edge or Safari. Firefox shows the page but skips a few scroll effects.
- Films and animated previews are stand-ins: still images with play buttons, to be replaced with real video.
- `<meta name="robots" content="noindex">` is set so it stays out of search results while it is a preview.
