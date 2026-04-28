# Dira · Personal Project Dashboard

מרכז שליטה אישי למעקב אחרי זכייה בפרויקט "דירה בהנחה / מחיר מטרה" ביהוד-מונוסון.

A Hebrew RTL personal dashboard for tracking a discounted-housing-program win in Israel.

## Live

[Open dashboard →](https://USERNAME.github.io/dira/) *(replace USERNAME after enabling GitHub Pages)*

## Stack

Single-file HTML web app, no build step:

- Vanilla JS · modular Data → State → UI architecture
- Hebrew RTL · Heebo (Google Fonts)
- Chart.js 4.4.0 · Leaflet 1.9.4 (OpenStreetMap)
- localStorage for notes, task state, file attachments
- PWA-ready (Add to Home Screen)

## Screens

1. **Dashboard** — executive summary, KPIs, alerts, what-changed
2. **Tasks** — categorized checklist with sources
3. **Financial** — benefit calculation, scenarios, charts
4. **Area** — interactive map, schools, amenities, urban development
5. **Market intel** — comparable listings, trends, news
6. **Documents** — knowledge hub with file uploads
7. **Health & Opportunity** — computed scores

## Privacy

Personal data (lottery letter scans, lawyer correspondence, etc.) lives in
`dira-uploads/` and is excluded from git via `.gitignore`. Only the dashboard
shell + mock data ship to the public repo.

## Local development

Just open `index.html` in any browser. No server needed.

```bash
# Optional: serve locally for fresh-fetch behavior
python3 -m http.server 8080
```
