# Best practices for scientific software development

This project contains files to generate the [Best practices for scientific software development guide](https://phac-modelling-hub.github.io/dev-practices/). Authorship information and acknowledgements can be found [here](https://phac-modelling-hub.github.io/dev-practices/index.html#acknowledgements).

# Reporting issues

If you find issues in the guide, such as typos, formatting/appearance issues, or unclear/missing information, please [report them](https://github.com/phac-modelling-hub/dev-practices/issues/new/choose).

# For contributors

The guide is a [Quarto Website](https://quarto.org/docs/websites/). The files generating the website are `index.qmd` (home page) and `.qmd`s in subdirectories corresponding to the guide's sections. The website settings are in `_quarto.yml`. Edit this file to change the appearance of the guide of the navigation elements. Preview the website locally using [these instructions](https://quarto.org/docs/websites/#website-preview).

## Publishing the site

The site is built and published automatically via GitHub Actions upon changes to the `main` branch. The workflow is defined in `.github/workflows
/publish-site.yml`.
