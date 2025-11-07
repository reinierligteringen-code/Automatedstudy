# Study App — Auto ZIP Import

**Workflow:** Upload a ZIP to `incoming/` → it auto-replaces the site on `main` → GitHub Pages deploys.

## Update flow
1. Go to `incoming/` → **Add file** → **Upload files** → drop `site.zip`.
2. **Commit** to `main`.

Notes:
- The ZIP must contain a built static site with `index.html` at the root (and `404.html` if you're using a SPA).
- Relative asset paths only (no absolute `/assets/...` paths).
