# SeaBee documentation

This repository contains technical documentation for the SeaBee project, rendered as a website using [Quarto](https://quarto.org/).

**The public version of the website is [here](https://seabee-no.github.io/documentation/)**.

## Updating manually

 1. Clone this repository (e.g. to NIVA's JupyterHub, which has Quarto installed) and switch to the `quarto_docs` branch.
 
 2. Modify the markdown in the `.qmd` files and, if necessary, update the header and sidebar menus in `_quarto.yml`.
 
 3. From a terminal, run `quarto render --output-dir docs`.
 
 4. Commit your changes and push them to GitHub. Once the build completes, the GitHub Pages version of the site (linked above) will be updated.
