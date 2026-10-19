# thebadideastudio.com

Source of [thebadideastudio.com](https://thebadideastudio.com), the website of Bad Idea Studio. Static HTML and CSS served by GitHub Pages from `main`, with no build step and no JavaScript.

| Path | Contents |
| --- | --- |
| `index.html` | studio page with the game tiles, social links and contact |
| `grand-theft-cocoa/` | Grand Theft Cocoa sign-up page, posting straight to the Kit form |
| `grand-theft-cocoa/thanks/`, `grand-theft-cocoa/confirmed/` | pages Kit redirects to after sign-up and after email confirmation |
| `privacy/` | privacy policy |
| `404.html` | page not found |
| `assets/css/site.css` | all styles |
| `assets/fonts/` | Inter Display subset as WOFF2, with its SIL Open Font License |
| `assets/social/` | link preview images (1200 × 630) |
| `favicon.ico`, `favicon.svg`, `apple-touch-icon.png` | browser and home screen icons |
| `assets/brand/` | studio logo and mark, dark (`#111113`) and white versions |
| `CNAME`, `.nojekyll`, `robots.txt`, `sitemap.xml` | GitHub Pages domain and crawler files |

## Adding a game

Add an `<li>` with an `article.game-tile` to the `.game-grid` list in `index.html`. The grid takes the next tile without layout changes.

## Local preview

```sh
python3 -m http.server 8790 --directory .
```

Then open http://localhost:8790/.
