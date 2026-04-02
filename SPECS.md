# DATS Practicum & Thesis Website — Specs Sheet

## Overview
A static website hosted on GitHub Pages (Jekyll) that consolidates all information, forms, timelines, and resources for Penn's DATS 5990 (Practicum) and DATS 9990 (Thesis) courses into a single, student-friendly hub.

## Goals
1. Replace the current multi-source setup (DATS website page + Google Doc + scattered links) with one canonical resource
2. Make the enrollment process clear and step-by-step for students
3. Enable easy content updates via Markdown files (no coding required)
4. Provide a professional, modern look with subtle Penn Engineering branding

## Tech Stack
- **Static site generator**: Jekyll (GitHub Pages native — no build step needed)
- **Hosting**: GitHub Pages at `chandrasg.github.io/dats-practicum`
- **Styling**: Custom CSS with Penn colors (Navy #011F5B, Red #990000) used as accents
- **Content format**: Markdown (.md) files — editable directly on GitHub's web UI
- **No JavaScript dependencies** — pure HTML/CSS for simplicity and speed

## Site Map

### 1. Home (`index.md`)
- Hero section: course name, one-line description, CTA to "Get Started"
- Quick overview: Thesis vs. Practicum at a glance (side-by-side comparison)
- Current semester key dates (pulled from `_data/timeline.yml`)
- Contact info: Sharath (Project Director), Staci (Program Manager)

### 2. Get Started (`pages/get-started.md`)
- Step-by-step enrollment process with numbered steps
- Direct links to: submission form, advisor agreement, Path@Penn
- What to prepare before starting (prerequisites, finding an advisor)
- Tips for finding a faculty advisor

### 3. Guidelines (`pages/guidelines.md`)
- Thesis requirements (2 CU, SEAS faculty advisor, reader, formatting)
- Practicum requirements (1-2 CU, report length, industry projects OK)
- Report formatting specs (page counts, citation styles, title page signatures)
- Presentation/poster requirements and specs (size, orientation, printing)
- Team project rules

### 4. Timeline (`pages/timeline.md`)
- Current semester milestones table (from `_data/timeline.yml`)
- Milestone descriptions: submission, mid-term check-in, final check-in, presentation day
- Academic calendar alignment (add/drop, withdrawal deadlines)
- Semester-specific details easily updatable in the YAML data file

### 5. FAQ (`pages/faq.md`)
- All FAQs from existing Google Doc (9+ questions)
- Organized with anchor links for easy navigation
- Expandable/collapsible sections (CSS-only, no JS)

### 6. Resources (`pages/resources.md`)
- Forms & templates (submission form, advisor agreement)
- Past student projects (link to Google Drive folder + brief description)
- Open faculty projects / DSSG projects
- Data sources (WRDS catalog)
- DATS Focus Areas Handbook
- Thesis formatting guidelines (SEAS link)
- Poster printing info and budget code

## Data Files (`_data/`)
- `timeline.yml` — semester dates, milestones (easy to update each semester)
- `contacts.yml` — faculty director, program manager contact info

## Design Decisions
- **Typography**: System font stack (clean, fast-loading)
- **Color palette**: White background, Navy (#011F5B) for headings/nav, Red (#990000) for accents/CTAs, light gray for section backgrounds
- **Layout**: Max-width 800px content area, generous whitespace, responsive
- **Navigation**: Top nav bar, sticky on scroll
- **Mobile**: Fully responsive, hamburger menu on small screens

## Content Update Workflow
1. Go to the GitHub repo
2. Navigate to the file you want to edit (e.g., `pages/timeline.md` or `_data/timeline.yml`)
3. Click the pencil icon to edit
4. Make changes in Markdown
5. Commit — site rebuilds automatically

## Assumptions
- The Google Form and advisor agreement PDF will continue to be hosted on Google (we link to them, not host them)
- Past project reports stay in the existing Google Drive folder
- Semester dates in `_data/timeline.yml` will be updated manually each semester
- The site is informational only — no student login, no form processing
