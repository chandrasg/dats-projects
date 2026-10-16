# DATS Practicum & Thesis Website

Website for Penn Data Science MSE students pursuing DATS 5990 (Practicum) or DATS 9990 (Thesis).

Live at: https://chandrasg.github.io/dats-projects

## What to Update and When

### Each semester — `_data/timeline.yml`
Update milestone dates for the new semester. Add a new block (e.g., `spring_2027:`) following the same format, then update **both** `current_semester` (the label) and `current_key` (the block name) at the top — changing only one leaves the Home and Timeline pages showing the wrong dates. To preview the following semester on the Timeline page, fill in `next_semester` and `next_key`; leave them as `""` to hide it. You can edit this directly on GitHub using the pencil icon — no local setup needed.

### Contact changes — `_data/contacts.yml`
Update faculty or staff names, emails, or roles here. All contact info across the site (home page, footer) pulls from this single file.

### Each Industry Capstone cycle — `_data/industry.yml`
Update the application, interview, and semester dates each cycle. Paste the application and sponsor-projects URLs between the quotes (`application_url`, `projects_url`) once they're posted — while empty, the Industry Capstone page shows a "contact the Program Manager" fallback automatically. Set `applications_open` to `false` after the deadline passes (the page then shows a "cycle closed" notice) and back to `true` when the next cycle opens.

### Page content — `pages/*.md` and `index.md`
Each page is a Markdown file — no HTML knowledge needed for most edits:
- `index.md` — Home page (overview, comparison table, quick links)
- `pages/get-started.md` — Enrollment steps
- `pages/guidelines.md` — Thesis & practicum requirements
- `pages/industry-capstone.md` — Industry Capstone content
- `pages/timeline.md` — Timeline page
- `pages/faq.md` — Frequently asked questions
- `pages/resources.md` — Forms, links, past projects

### Navigation or site title — `_config.yml` and `_includes/header.html`
Change the site title/description in `_config.yml`. Add or remove nav links in `_includes/header.html`.

### Styling — `assets/css/style.css`
Penn colors, fonts, and layout. Rarely needs changes.
