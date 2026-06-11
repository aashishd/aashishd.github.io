# aashishd.github.io

Personal portfolio / web resume, live at **https://aashishd.github.io**.

- One static file: `index.html`. No framework, no build step, no dependencies —
  embedded CSS, native `<details>` collapsibles, dark mode via
  `prefers-color-scheme`.
- Deploys automatically via GitHub Pages on every push to `main`.
- Content is derived from the canonical resume source (kept privately); phone
  number is deliberately omitted from the public page.

## Custom domain (planned, not yet active)

The intent is to serve this at the apex **adhiman.dev** (DNS on Cloudflare).
When hooking it up: add a `CNAME` file containing `adhiman.dev`, then in
Cloudflare DNS point the apex at GitHub Pages per
[GitHub's custom-domain docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site),
and enable "Enforce HTTPS" in the repo's Pages settings.
