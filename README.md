# asirohi.com — static site

A tiny, old‑web style personal site. No build tools, no JS required.

## Local preview
Open `index.html` directly in your browser.

## Deploy (GitHub Pages)
1. Create a repo named `<your-username>.github.io` on GitHub.
2. Push these files to the repo root.
3. In the repo: Settings → Pages → Source: “Deploy from a branch”, branch: `main`.
4. Add your custom domain in Pages: `www.asirohi.com` and enable “Enforce HTTPS”.
5. At your registrar: add a CNAME record: `www` → `<your-username>.github.io` and set a forward from `asirohi.com` → `www.asirohi.com`.
