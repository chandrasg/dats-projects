# DATS Practicum & Thesis Website

Website for Penn Data Science MSE students pursuing DATS 5990 (Practicum) or DATS 9990 (Thesis).

Live at: https://chandrasg.github.io/dats-projects

## What to Update and When

### Semester dates — `_data/timeline.yml`
**The site switches semesters automatically.** Each semester under `terms` has an `ends` date; the Home page shows the earliest semester that hasn't ended, and the Timeline page also shows the next one. A semester drops off the day after its `ends` date, judged by the visitor's own clock, so stale dates never show even without a rebuild. If no upcoming semester has been added, the site says dates will be posted soon rather than showing old ones.

To add a semester: add an entry under `terms` (oldest first; `key` matches the milestone block name, `ends` is `YYYY-MM-DD`), then add the milestone block (copy an existing one). You can edit this directly on GitHub using the pencil icon — no local setup needed.

A monthly scheduled job reads the [Penn Engineering Graduate Academic Calendar](https://grad.engineering.upenn.edu/graduate-academic-calendar/), drafts upcoming semesters and fills in "TBD" dates, and opens a pull request — review and merge it to publish. It derives dates by these rules, and never changes a date a person has already set:
- Submit project form & advisor agreement — by the course selection (add) deadline
- Mid-semester check-in — by the "drop period ends" date
- Final check-in (project report due) — before the last day to withdraw
- Thesis submission — the calendar's thesis due date for that term's graduates
- DATS Presentation Day — set by the program; stays "TBD" until someone fills it in

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
