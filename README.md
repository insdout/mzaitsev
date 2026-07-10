# mzaitsev

Personal website and blog of **Michael Zaitsev** — [insdout.github.io/mzaitsev](https://insdout.github.io/mzaitsev/).

## Development

```bash
bundle install
bundle exec jekyll serve            # http://localhost:4000/mzaitsev/
bundle exec jekyll build            # production build to _site/
```

## Deployment

Pushing to `main` triggers the **Deploy site** GitHub Action, which builds the
site and publishes it to the `gh-pages` branch (served by GitHub Pages).

## Structure

- `_pages/` — Home, CV, Blog
- `_posts/` — blog posts
- `_config.yml` — site configuration
- `assets/img/me.png` — profile picture

---

Built with the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (MIT).
