# Chintan Dhamecha — Portfolio

Single-page "Control Tower" portfolio for Chintan Dhamecha — Digital Transformation & Operations.

**Live site:** https://bizchintan.github.io/

## What's here

| File | Purpose |
|---|---|
| `index.html` | The entire site — HTML, CSS and JS in one file, no build step, no dependencies |
| `mba_project_diagram.png`, `bachelors_project_diagram.png` | Diagrams shown inside the Education → project panels |
| `assets/certs/*` | Certificate images shown in the Certifications lightbox |
| `ambient-background.mp3`, `blackhole-collapse.mp3` | Audio, gated behind the site's Sound toggle (nothing autoplays) |
| `.nojekyll` | Tells GitHub Pages to serve files as-is |

## Running locally

It's a static file — open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000    # then visit http://localhost:8000
```

## Deploying

Push to the `main` branch of a repo named `bizchintan.github.io`, then enable
**Settings → Pages → Deploy from branch → main / root**.
