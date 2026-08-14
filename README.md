# Boxiong's personal website

This repository contains the Jekyll source for [boxiong.io](https://boxiong.io/).
Edit and commit on `master`. GitHub Actions builds the site and publishes the
generated files to `gh-pages`; do not edit `gh-pages` by hand.

## First-time setup on macOS

```bash
brew install ruby@3.3 imagemagick
bin/setup
```

The setup script installs Ruby gems into the ignored `vendor/bundle` directory,
so it does not modify the system Ruby.

## Preview while editing

```bash
bin/serve
```

Open <http://127.0.0.1:4000/>. Refresh the browser after source files change.
Stop the server with `Ctrl-C`.

To run the same production build used for deployment:

```bash
bin/build
```

Generated output is written to the ignored `_site` directory.

## Where to edit content

- `_pages/about.md`: home/about page
- `_pages/publications.md`: publications page layout and introduction
- `_bibliography/papers.bib`: publication entries
- `_news/`: news items
- `_projects/`: project entries
- `_config.yml`: site title, links, social profiles, and global settings
- `assets/img/`: profile, publication, and project images

## Publish changes

```bash
git add <changed-files>
git commit -m "Update website content"
git push origin master
```

Pushing `master` starts `.github/workflows/deploy.yml`. That workflow builds
Jekyll and replaces the generated `gh-pages` branch automatically.
