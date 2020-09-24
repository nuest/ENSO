# ENSO

This repository contains the code and data for the article

> Muenchow, J., Dieker, P., Böttcher, T., Brock, J., Didenko, G., Fremout, T., Jakubka, D., Jentsch, A., Nüst, D., Richter, M., Rodríguez, E.F., Rodríguez, R.A., Rollenbeck, R., Salazar Zarsosa, P., Schratz, P. and Brenning, A. (2020), **Monitoring and predictive mapping of floristic biodiversity along a climatic gradient in ENSO's terrestrial core region, NW Peru**. Ecography. doi: [10.1111/ecog.05091](https://doi.org/10.1111/ecog.05091)

## Reproduce locally

To install all required packages for this analysis, please execute

```r
renv::init()
renv::install()
```

from the repository root.
The _renv_ package is the successor of the _packrat_ package and can be [installed from CRAN](https://cran.r-project.org/package=renv).
This will create a project-based R library in a subdirectory `renv` based on the lockfile `renv.lock`, with R packages being kept at a specific version for better reproducibility.

## Contents

This repository contains the data, code, and text for the article and realises a [research compendium](https://research-compendium.science/).

### Text

The main body of the article can be found in `docs/enso_comp.Rmd`.
This [R Markdown](https://rmarkdown.rstudio.com/) source be rendered to a PDF document for easier reading, printing, etc.
The file `docs/supplementary_information.Rmd` contains Appendix 1-4 of the article.
The file `docs/title_page.Rmd` contains the authors, article metadata, and abstract.

### Data

Zenodo deposit

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3981436.svg)](https://doi.org/10.5281/zenodo.3981436)

### Code

Directory `R` ...

Directory `code` ...
