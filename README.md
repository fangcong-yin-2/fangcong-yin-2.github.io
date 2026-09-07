# fangcong-yin-2.github.io

Personal academic website for Fangcong Yin — <https://fangcong-yin-2.github.io>

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme.

## Editing content

| What                | Where                      |
| ------------------- | -------------------------- |
| Bio / homepage      | `_pages/about.md`          |
| Publications        | `_bibliography/papers.bib` |
| CV (PDF)            | `assets/pdf/CV.pdf`        |
| Interest page       | `_pages/interest.md`       |
| Social links, email | `_data/socials.yml`        |
| Venue badge colors  | `_data/venues.yml`         |
| Coauthor links      | `_data/coauthors.yml`      |
| Site settings       | `_config.yml`              |

Papers marked `selected = {true}` in `papers.bib` appear on the homepage.

## Running locally

```bash
bundle install
bundle exec jekyll serve --livereload   # http://localhost:4000
```

Requires Ruby 3.x and ImageMagick (`brew install ruby imagemagick`).

## Deployment

Pushing to `master` triggers `.github/workflows/deploy.yml`, which builds the site
and publishes it to the `gh-pages` branch. GitHub Pages serves from `gh-pages`.

## License

Theme licensed under the MIT License — see [LICENSE](LICENSE).
