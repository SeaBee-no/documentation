# SeaBee documentation

This repository contains technical documentation for the SeaBee project, rendered as a website using [Quarto](https://quarto.org/).

**The public version of the website is [here](https://seabee-no.github.io/documentation/)**.

## Updating

### GitHub actions

A new version of the website is automatically rendered to the `gh-pages` branch of this repository whenever changes are pushed to `main` (see [here](https://github.com/SeaBee-no/documentation/blob/main/.github/workflows/quarto-publish.yml)). To update, simply edit the `.qmd` files on `main`, then commit and push the changes. Once the build script finishes, a new version of the site will be available.

### Manual updates

**Manual updates should not be necessary**. If they are:

1.  Clone this repository (e.g. to NIVA's JupyterHub, which has Quarto installed)

2.  Modify the markdown in the `.qmd` files and, if necessary, update the header and sidebar menus in `_quarto.yml`

3.  From a terminal, run `quarto render`

4.  Commit your changes and push them or create a PR if you use a different branch
