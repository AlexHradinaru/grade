# Gradé

An image studio creating on-model campaigns for fashion, beauty and lifestyle brands.

**Live site:** https://alexhradinaru.github.io/grade/

## About

Single self-contained `index.html` — no build step, no dependencies. Vanilla JS with
hash-based routing. Fonts load from Google Fonts; everything else ships with the page.

```
index.html     the whole site (markup, styles, data, routing)
img_*.jpg      hero, disciplines and casting portraits
ca_*.jpg       campaign — Maison Verde
cb_*.jpg       campaign — Atelier Nord
cc_*.jpg       campaign — Suisse Objet
```

## Editing

Everything you'd want to change sits at the top of the `<script>` block in `index.html`:

- `IMG` — file names for the hero, disciplines and casting portraits
- `CAMPAIGNS` — campaign titles, years, notes and their shots
- `FACES` — casting references and their looks
- `DISCIPLINES`, `PROCESS`, `ENGAGEMENTS`, `DETAILS` — all site copy

Colours and type sizes are CSS custom properties in `:root`.

## Running locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000

## Note

Work-in-progress portfolio site.

All campaigns are marked **Concept** — self-initiated work made to demonstrate
range, not client commissions. Gradé is not affiliated with, authorised by or
endorsed by any brand shown.

The studio address and contact email are also **placeholders**. Replace them
before any commercial use.
