# Jialin Chen

Academic homepage built with [AcademicPages](https://github.com/academicpages/academicpages.github.io) and Jekyll. The public address is [https://chialinchen.github.io/](https://chialinchen.github.io/).

Edit the homepage in `_pages/about.md`, the CV page in `_pages/cv.md`, and the sidebar in `_config.yml`. The portrait is `images/profile.jpg`. Do not add the CV PDF to this site.

## Publish

This folder is a local Git repository on `main`. It does not have a remote yet. Create an empty public repository named `ChialinCHEN.github.io`, with no README, then run:

```bash
cd /Users/chialinchen/ChialinCHEN.github.io
git add -A
git commit -m "Add the academic homepage"
git remote add origin https://github.com/ChialinCHEN/ChialinCHEN.github.io.git
git push -u origin main
```

Then, in the repository on GitHub, open **Settings → Pages** and set **Source** to **GitHub Actions**. The workflow in `.github/workflows/jekyll.yml` builds the site.

## Local preview

Ruby 3.1 or newer is required. The system Ruby on this Mac is too old for the template.

```bash
bundle install
bundle exec jekyll serve
```

Open the address Jekyll prints, usually `http://127.0.0.1:4000/`.
