Website content release: v2.0

# Tarekegn Dejen Mengistu academic website

This repository contains the cleaned Jekyll/GitHub Pages source for the academic website of **Dr. Tarekegn Dejen Mengistu**.

Target live URL: `https://tdmengistu.github.io/`

## Repository name

The GitHub repository must be named exactly:

```bash
tdmengistu.github.io
```

## Local build commands

```bash
bundle install
bundle update
bundle exec jekyll serve
bundle exec jekyll build
```

## GitHub Pages deployment

This repository includes `.github/workflows/pages.yml`, which builds and deploys the Jekyll site with GitHub Actions from the `main` branch. In GitHub repository settings, set **Pages** to deploy from **GitHub Actions**.

## Public navigation

Home | Publications | Presentations | Awards | Updates | CV

## Content policy applied

The public pages avoid phone numbers and private references. The publications page includes only published works from the CV; under-review and in-preparation manuscripts are excluded.

## Version 3 publication upgrade

Version 3 hosts all 12 journal-paper PDFs locally, uses the complete published abstracts in the collapsible ABS panels, preserves the publication control order (ABS, BIB, DOI, PDF, Dimensions), and adds the March 2024 UST Travel Grant update.
