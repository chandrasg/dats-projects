# DATS Practicum & Thesis Website

Website for Penn Data Science MSE students pursuing DATS 5990 (Practicum) or DATS 9990 (Thesis).

Live at: https://chandrasg.github.io/dats-projects

## Setup & Deployment

### 1. Create the GitHub repo

```bash
# From this directory:
cd dats-practicum-site
git init
git add .
git commit -m "Initial site build"

# Create the repo on GitHub (requires gh CLI):
gh repo create dats-projects --public --source=. --push

# Or manually:
# 1. Go to https://github.com/new
# 2. Create repo named "dats-projects"
# 3. Push:
git remote add origin https://github.com/chandrasg/dats-projects.git
git branch -M main
git push -u origin main
```

### 2. Enable GitHub Pages

1. Go to **Settings** → **Pages** in your repo
2. Under "Source", select **Deploy from a branch**
3. Select **main** branch, **/ (root)** folder
4. Click Save
5. Wait ~60 seconds, your site will be at: `https://chandrasg.github.io/dats-practicum`

### 3. (Optional) Test locally

```bash
gem install bundler jekyll
bundle install
bundle exec jekyll serve
# Open http://localhost:4000/dats-projects/
```

## Updating Content

### Update semester dates
Edit `_data/timeline.yml` — change dates, add new semesters. You can do this directly on GitHub's web interface (pencil icon).

### Update contact info
Edit `_data/contacts.yml`.

### Update page content
Edit any `.md` file in `pages/` or `index.md`. Content is in Markdown — no HTML knowledge needed for most updates.

### File structure
```
_config.yml          # Site settings (rarely needs changes)
_data/
  timeline.yml       # Semester dates (update each semester)
  contacts.yml       # Faculty/staff contact info
_includes/
  header.html        # Navigation bar
  footer.html        # Footer
_layouts/
  default.html       # Page template
assets/css/
  style.css          # Styling
index.md             # Home page
pages/
  get-started.md     # Enrollment steps
  guidelines.md      # Thesis & practicum requirements
  timeline.md        # Timeline page
  faq.md             # Frequently asked questions
  resources.md       # Forms, links, past projects
```
