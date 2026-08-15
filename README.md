# Nishant S. — Portfolio

Personal portfolio site for Nishant S. — Full-stack developer & AI/ML student (Greater Chennai Area).

Single-page static site: React-free, no build step. Plain HTML/CSS/JS.

## Stack
- HTML5 + CSS (custom properties, no framework)
- Vanilla JS (IntersectionObserver for scroll reveals & nav scroll-spy, Canvas for the hero neural-net animation)
- Fonts: [Fraunces](https://fonts.google.com/specimen/Fraunces) (display) + [Inter](https://fonts.google.com/specimen/Inter) (body/UI)

## Run locally
No build step — just open the file, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy (GitHub Pages)
1. Push this repo to GitHub (already done if you're reading this on GitHub).
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — your site will be live at `https://<username>.github.io/<repo-name>/` within a minute or two.

## Structure
```
index.html        # the whole site
favicon.svg        # browser tab icon
assets/og-image.png # social share preview image
```

## Content updates
All copy lives directly in `index.html` — search for the section you want (`id="work"`, `id="toolkit"`, `id="experience"`, etc.) and edit the text or `panel-card` blocks directly. No templating/build step required.

## To do
- [ ] Swap the "Ask me about it" project cards for real project write-ups + links/screenshots
- [ ] Add a downloadable resume PDF and wire up a "Resume" button
- [ ] Add real project screenshots to the Work section
