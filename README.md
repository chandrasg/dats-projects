# DATS Practicum & Thesis Website

Website for Penn Data Science MSE students pursuing DATS 5990 (Practicum) or DATS 9990 (Thesis).

Live at: https://chandrasg.github.io/dats-projects

## What to Update and When

### Each semester — `_data/timeline.yml`
Update milestone dates for the new semester. Add a new block (e.g., `fall_2026:`) following the same format, and update `current_semester` at the top. You can edit this directly on GitHub using the pencil icon — no local setup needed.

### Contact changes — `_data/contacts.yml`
Update faculty or staff names, emails, or roles here. All contact info across the site (home page, footer) pulls from this single file.

### Page content — `pages/*.md` and `index.md`
Each page is a Markdown file — no HTML knowledge needed for most edits:
- `index.md` — Home page (overview, comparison table, quick links)
- `pages/get-started.md` — Enrollment steps
- `pages/guidelines.md` — Thesis & practicum requirements
- `pages/timeline.md` — Timeline page
- `pages/faq.md` — Frequently asked questions
- `pages/resources.md` — Forms, links, past projects

### Navigation or site title — `_config.yml` and `_includes/header.html`
Change the site title/description in `_config.yml`. Add or remove nav links in `_includes/header.html`.

### Styling — `assets/css/style.css`
Penn colors, fonts, and layout. Rarely needs changes.
