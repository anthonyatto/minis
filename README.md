# minis
a collection of mini projects.

## Projects

### dashboard-demo

A Quarto dashboard demo showing teacher candidate certification progress. Includes interactive tables (DT) and a Leaflet map.

**Live site:** [https://anthonyatto.github.io/minis/](https://anthonyatto.github.io/minis/)

## Publishing to GitHub Pages

The dashboard is published as a static site to the `gh-pages` branch. To republish after making changes on `main`:

```bash
cd /path/to/minis
quarto publish gh-pages dashboard-demo/dashboard.qmd --no-prompt
```

Requirements:

- [Quarto](https://quarto.org/docs/get-started/) must be installed
- R packages: `dplyr`, `readr`, `stringr`, `purrr`, `leaflet`, `DT`, `magrittr`, `here`
