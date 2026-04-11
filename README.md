# Best practices for scientific software development

This project contains files to generate the [Best practices for scientific software development guide]. You can find out more about the project [here]().

# Reporting issues

If you find issues in the guide, please report them by [opening an issue](). If you are opening an issue, please use labels to categorize it. The three most relevant labels are likely to be:

1. `typo`: There is a typo
1. `formatting/appearance issues`: Something looks wrong visually
1. `unclear/missing info`: Text is unclear or information is missing

# Contributing to this guide

The guide is a [Quarto Website](https://quarto.org/docs/websites/):

1. The files generating the website are `index.qmd` (guide home page at the top level of the repository) and all `.qmd` files in `docs/`. Edit these to change the contents of the website.
1. The website settings are in `_quarto.yml`. Edit this file to change the appearance of the guide of the navigation elements.
1. Preview the website using [these instructions](https://quarto.org/docs/websites/#website-preview).

## Continuous integration

We use a [GitHub Actions](https://docs.github.com/en/actions/get-started/quickstart) to builds and deploy the website when the `main` branch is changed. Build instructions are in `.github/workflows/publish-website.yml`.