# Miguel Moncada Isla — CV site

Single-page CV built as a static site. No build step.

## Local preview

```bash
cd cv-site
python3 -m http.server 8000
# open http://localhost:8000
```

## Layout

- `index.html` — page content
- `assets/styles.css` — all styling (light + dark, print)
- `assets/main.js` — theme toggle + footer year

## Deploying to GitHub Pages

This site is intended to be published as the user site at
`https://mmoncadaisla.github.io`.

1. Create a new GitHub repo named `Mmoncadaisla.github.io`.
2. Push the contents of this folder (not the folder itself) to the `main` branch.
3. In repo **Settings → Pages**, set the source to `Deploy from a branch`, branch `main`, folder `/`.
4. Wait a minute or two — the site is live at `https://mmoncadaisla.github.io`.

If you'd rather host it as a project page (`https://mmoncadaisla.github.io/cv`),
push to a repo named `cv` instead and enable Pages the same way.
