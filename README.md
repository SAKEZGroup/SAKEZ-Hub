# SAKEZ Group — Hub (Situs Induk)

Situs induk resmi **SAKEZ Group** — `sakezgroup.com`.
Static site, siap untuk **Cloudflare Pages**.

## Isi repo
- `index.html` — halaman Hub (single-file, self-contained; semua aset ter-inline)
- `_headers` — security headers + content-type
- `_redirects` — `www.sakezgroup.com` → `sakezgroup.com` (301)
- `robots.txt`, `sitemap.xml`, `site.webmanifest`

## Deploy (Cloudflare Pages)
- Framework preset: **None**
- Build command: **(kosong)**
- Output directory: **`/`**
- Custom domain: `sakezgroup.com` + `www.sakezgroup.com`

Setelah repo tersambung ke project Cloudflare `sakez-hub`, setiap `git push` ke branch `main` akan auto-deploy.

## Sumber desain
Halaman dibangun dari `SAKEZ Group Hub.dc.html` lalu di-bundle menjadi `index.html` (self-contained).
Untuk update: perbarui sumber desain, re-bundle, ganti `index.html`, commit & push.
.
