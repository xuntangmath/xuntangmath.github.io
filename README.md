# Xun Tang - Academic Website

Personal academic website for Xun Tang, Assistant Professor in the Department of Mathematics at HKUST. The site uses the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template.

Published at <https://xuntangmath.github.io>.

## Local preview

```bash
bundle config set --local path vendor/bundle
bundle install
bundle exec jekyll serve --baseurl ""
```

Open <http://localhost:4000> after the server starts.

## Edit the website

Every public page is a Markdown file in `_pages/`:

- `_pages/about.md` - homepage and biography
- `_pages/research.md` - research overview and selected papers
- `_pages/cv.md` - complete web CV
- `_pages/404.md` - not-found page

Edit `_config.yml` for profile details and site-wide settings. Files under `_layouts/` and `_includes/` belong to the theme and normally do not need editing. The `_site/` directory is generated automatically and must not be edited.

`files/Xun_Tang_Resume.pdf` is the optional downloadable CV. The editable website CV lives in `_pages/cv.md`.

The GitHub repository must be named `xuntangmath.github.io` so GitHub Pages publishes it at the root URL above.
