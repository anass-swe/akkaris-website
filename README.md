# Akkaris — Studio Website

Static site for akkaris.dev / GitHub Pages.

## Files

```
akkaris-site/
├── index.html      ← Homepage (hero, games, about)
├── privacy.html    ← Privacy policy (all games)
├── style.css       ← Full brand stylesheet
└── README.md
```

## GitHub Pages deployment

1. Create a new repo named `akkaris.github.io` (or `your-username.github.io`)
2. Push these files to the `main` branch root
3. Go to repo Settings → Pages → Source: Deploy from branch → main → / (root)
4. Site goes live at `https://your-username.github.io`

### Custom domain (optional)
- Add a `CNAME` file containing your domain (e.g. `akkaris.dev`)
- Point your domain's DNS to GitHub Pages IPs:
  ```
  A     185.199.108.153
  A     185.199.109.153
  A     185.199.110.153
  A     185.199.111.153
  ```

## Before publishing checklist

- [ ] Replace `<!-- TODO: update date before publishing -->` in privacy.html with today's date
- [ ] Update the Google Play download link in index.html (replace `href="#"` with real URL)
- [ ] Update `contact@akkaris.dev` and `privacy@akkaris.dev` with your real email address
- [ ] Update the OG meta tags in index.html with your real domain URL
- [ ] Add `og:image` with a 1200×630 screenshot once the site is live
- [ ] Add a real `CNAME` file if using a custom domain

## Adding a new game

1. In `index.html`, duplicate the Splitline `<article class="game-card">` block
2. Update title, description, tags, download link
3. In `privacy.html`, duplicate the Splitline `<div class="privacy-game-block">` block
4. Update all game-specific policy text

## Fonts

Uses Google Fonts (loaded from CDN):
- **Instrument Serif** — display / hero headings
- **DM Sans** — body, UI, labels

No build step required. Pure HTML/CSS/JS.
