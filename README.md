# Kritika Kumari — academic website

This repository contains a lightweight Jekyll academic portfolio for Kritika Kumari. It is designed for GitHub Pages and follows the spirit of clean academic templates such as al-folio while keeping the codebase small and easy to customize.

## Local development

1. Install Ruby and Bundler.
2. Install dependencies:

   ```bash
   bundle install
   ```

3. Run the site locally:

   ```bash
   bundle exec jekyll serve
   ```

4. Open <http://localhost:4000>.

## Content structure

- `_config.yml` stores site metadata, navigation, author details, and collections.
- `index.md` is the home page.
- `_pages/` contains standalone pages for research, projects, and CV content.
- `_projects/` contains project entries that appear on the Projects page.
- `_layouts/` and `_includes/` define reusable Jekyll templates.
- `_sass/theme.scss` and `assets/css/main.scss` define the visual design.

## Customization ideas

- Add a profile photo and publication list.
- Create more project entries under `_projects/`.
- Expand `_pages/cv.md` with education, awards, teaching, and service.
- Add Google Scholar, ORCID, LinkedIn, or lab links to `_config.yml` and `_includes/footer.html`.
