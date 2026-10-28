# Sunrun Academy Analytics (mockup)

Interactive design mockup of the Academy performance dashboard. **All numbers are sample data.**

- `index.html` is self-contained: no build step, no dependencies beyond Google Fonts.
- Pages: Overview, Funnel & Retention, Training Impact, Areas to Improve, Assignments.
- Filters: channel → region → office, plus MoM / QoQ / YoY comparison.
- Nothing a viewer clicks (e.g. "Assign") is saved; it resets on reload.

## Publish with GitHub Pages

1. Create a **public** repo (e.g. `academy-dashboard`) and upload `index.html` and this README.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)` → Save.
3. After ~1 minute it's live at `https://<your-username>.github.io/academy-dashboard/`.

The page carries a `noindex` tag so search engines don't list it; anyone with the link can still open it.
