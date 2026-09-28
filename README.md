# travel-tour-web-demo (Stillpoint studio site)

Static single-page site. Ready for Cloudflare Pages — no build step.

## Deploy on Cloudflare Pages

### Option A — via GitHub (recommended)
1. Push this folder to GitHub (repo `travel-tour-web-demo`).
2. Go to Cloudflare Dashboard → **Workers & Pages → Create → Pages → Connect to Git**.
3. Select repo `travel-tour-web-demo`.
4. Build settings:
   - Framework preset: `None`
   - Build command: *(empty)*
   - Build output directory: `/` (root)
5. Deploy. Every `git push` to `main` redeploys automatically.

### Option B — direct upload
Cloudflare Dashboard → **Workers & Pages → Create → Pages → Upload assets**,
drag in `index.html` (+ `404.html`, `_headers`, `robots.txt`).

## Local preview

Just open `index.html`, or:

```bash
npx serve .
# or
python -m http.server 8000
```
