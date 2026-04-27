# Mad Giant Studios — Single Page Website

A dark, minimal, premium-feel single-page site for **Mad Giant Studios**.
Built with pure **HTML + CSS + JavaScript** — no build step required.

## Run

Just double-click `index.html`, or serve locally:

```bash
# Python (any version)
python -m http.server 8000
# then open http://localhost:8000
```

## File structure

```
mad-giant-studios/
├── index.html      # Markup
├── styles.css      # Styling
├── script.js       # Interactions (smooth scroll, reveal-on-scroll, mobile nav)
└── assets/         # Logo + game cover + team photos (placeholders for now)
```

## Replacing placeholders

- **Logo**: replace `assets/logo.svg`
- **Real Deal cover**: replace `assets/real-deal.svg`
- **Real Deal trailer**: edit the `data-yt` attribute on the iframe in `index.html`
- **Team photos**: replace `assets/team-*.svg` with real photos (jpg/png) and update the `<img src>` in `index.html`

Sections: Hero · About · Games · Team
