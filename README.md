# Showrov Ghosh Roy — Portfolio

Minimal, Portavia-inspired portfolio built with plain HTML, CSS, and JavaScript.
No build tools, no frameworks — ready to deploy anywhere.

## Structure

```
├── index.html      # All page content
├── css/style.css   # Styles, themes, animations
└── js/script.js    # Theme toggle, scroll reveals, cursor, form
```

## Deploy to GitHub Pages

Your site already lives at `showrovghoshroy.github.io`, so:

1. Open your existing repo `Showrovghoshroy/showrovghoshroy.github.io`
2. Delete the old files (or move them into an `old/` folder)
3. Upload `index.html`, the `css/` folder, and the `js/` folder to the repo root
4. Commit — the site updates at https://showrovghoshroy.github.io/ within a minute or two

## Customizing

- **Profile photo** — the hero image currently loads from your old site's URL.
  For reliability, add your photo to the repo (e.g. `images/me.png`) and change
  the `src` of the hero `<img>` in `index.html`.
- **Accent color** — edit `--accent` in `css/style.css` (`:root` for light,
  `html.dark` for dark mode).
- **Contact form** — currently opens the visitor's email app (mailto). For a
  hosted form, sign up at formspree.io and replace the form's submit handler
  with your Formspree endpoint.
- **Dark mode** — follows the visitor's system preference by default; the
  navbar button toggles it manually.
