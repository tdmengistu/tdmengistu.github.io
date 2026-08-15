# Build and publishing notes

## Local setup

Run these commands from the repository root:

```bash
bundle install
bundle update
bundle exec jekyll serve
bundle exec jekyll build
```

## GitHub Pages publishing

1. Create or rename the GitHub repository to `tdmengistu.github.io`.
2. Push this cleaned site to the `main` branch.
3. In GitHub repository settings, open **Pages**.
4. Set the source to **GitHub Actions**.
5. Confirm that `.github/workflows/pages.yml` runs successfully.
6. Confirm the live URL is `https://tdmengistu.github.io/`.

## Deployment-critical configuration

`_config.yml` is set to:

```yaml
url: https://tdmengistu.github.io
baseurl: ""
```

## Content quality control applied

- Former template-owner pages, posts, demo projects, teaching content, repository demos, Docker workflows, and unsupported bibliography tooling were removed.
- The public pages do not display a phone number or private references.
- The Publications page contains only published works from the CV.
- The complete publication list appears only on `/publications/`.
- Navigation is: Home | Publications | Presentations | Awards | Updates | CV.

## CV content policy

The website CV intentionally excludes **Data Science and AI/ML Training** and **Technical Skills**. No downloadable PDF CV is included. A separate submission CV may contain training and skills when appropriate.


Version 12 restores the 2025–2026 Updates and applies a responsive fixed-width left date column to both Updates and Honors and Awards.
