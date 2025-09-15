# jekyll-designer-portfolio

A Jekyll-based portfolio site. Clean typography, responsive layouts, and simple content structure.

## Features
- Jekyll + Liquid templates
- Sass partials in `_sass/`
- Includes for nav/footer/cards in `_includes/`
- Blog posts in `_posts/`

## Structure
```

\_includes/   # HTML partials
\_layouts/    # Page/post layouts
\_posts/      # Blog posts (YYYY-MM-DD-title.md)
\_sass/       # Sass partials
\_site/       # Build output (ignored)
css/         # Compiled CSS (optional)
images/      # Site images

````

## Local Development
> Requires Ruby and Bundler. On macOS: `brew install ruby` (or use a Ruby version manager).

```bash
bundle install
bundle exec jekyll serve --livereload
````

## Deployment

* Push to GitHub. If using GitHub Pages, enable Pages in repo settings and set the build source.
* Avoid committing `_site/`.

## License

Choose a license (e.g., MIT) or keep private.
