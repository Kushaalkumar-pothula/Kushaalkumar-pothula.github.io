# Kushaalkumar-pothula.github.io

Personal academic website of Kushaal Kumar Pothula, built with
[Jekyll](https://jekyllrb.com) on the
[Academic Pages](https://github.com/academicpages/academicpages.github.io) template
and hosted on GitHub Pages.

## Local development

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>.

## Structure

- `_config.yml` — site settings, sidebar profile and links
- `_data/navigation.yml` — top navigation
- `_pages/about.md` — front page
- `_pages/projects.md`, `_pages/blog.md` — placeholder pages
- `_pages/cv.md` — CV page with the embedded PDF
- `_sass/theme/_default_light.scss`, `_sass/theme/_default_dark.scss` — colour themes
- `images/profile.png` — sidebar avatar (replace with your own photo)
