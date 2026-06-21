# chloeandchris.net

Wedding site! Minimal, fast, mobile-friendly, single static page 

## Editing

All content lives in `index.html`. Sections marked `[ ... ]` (greyed out) are placeholders to replace text w actual info

## Hosting

Served via **GitHub Pages** from the `main` branch. The `CNAME` file points the site at the custom domain `chloeandchris.net`.

### DNS (at Namecheap)

Under *Domain List &rarr; Manage &rarr; Advanced DNS*, set:

| Type  | Host | Value           |
|-------|------|-----------------|
| A     | @    | 185.199.108.153 |
| A     | @    | 185.199.109.153 |
| A     | @    | 185.199.110.153 |
| A     | @    | 185.199.111.153 |
| CNAME | www  | chloeimus.github.io. |

Remove Namecheap's default "parking"/redirect records first. Allow up to ~30 min for DNS to propagate, then enable "Enforce HTTPS" in the repo's Pages settings.
