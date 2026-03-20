# Bay Window — Events Page

Auto-generated weekly events listing page for [The Bay Window](https://www.baywindow.ie) newsletter covering Dún Laoghaire-Rathdown.

## How it works

1. Every Monday, an n8n workflow reads events from a Google Sheet
2. The raw data is sent to the Claude API which filters, deduplicates, and generates the full HTML
3. The generated page is committed to this repo as `index.html`
4. Cloudflare Pages serves it at [events.baywindow.ie](https://events.baywindow.ie)

## Files

- `index.html` — Current week's events (auto-generated, do not edit)
- `_template.html` — HTML template Claude populates each week
- `hero.jpg` — Hero image (upload manually, stays fixed)

## Archive

Past weeks are stored as `YYYY-MM-DD.html` (the Monday start date).
