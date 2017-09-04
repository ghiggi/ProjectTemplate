<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Last-changedate](https://img.shields.io/badge/last%20change-2017--09--04-brightgreen.svg)](https://github.com/benmarwick/researchcompendium/commits/master)

[![minimal R version](https://img.shields.io/badge/R%3E%3D-3.3.3-brightgreen.svg)](https://cran.r-project.org/)

[![Licence](https://img.shields.io/github/license/mashape/apistatus.svg)](http://choosealicense.com/licenses/mit/)

[![ResearchGate](https://img.shields.io/badge/ResearchGate-ETHZ-green.svg)](https://www.researchgate.net/profile/Gionata_Ghiggi)

Research Project
----------------

Published in: Ghiggi G., ....

DOI : <http://dx.doi.org/xxxxxxx>

### Overview of contents

This repository contains materials to reproduce .... to use ............ The repository contains all data, code, and text associated with the publication.

The `Rmd` files in the `docs/vignettes/` directory contain - details of how all the analyses reported in the paper were conducted - instructions on how to rerun the analysis to reproduce the same results. - R code to recreate the figures included in the manuscript

The `data/` directory contains all the raw data, clean & tidy data and the final data

The `script/` directory contains: - the manuscript as submitted (in MS Word format) and it's Rmd source file - all the data files (in CSV format, in the `data/` directory)
- supplementary information source files (in R markdown format) and executed versions - all the figures that are included in the paper (in the `figures/` directory)

### Reproducibility

This repository is organized similarly to an R package. The R package structure is used to help manage dependencies and to to take advantage of continuous integration for automated code testing.

### Package dependencies

I used [RStudio](http://www.rstudio.com/products/rstudio/) on Ubuntu 16.04 and Windows 7. The package has a number of dependencies on other R packages.

These are listed at - packrat - checkpoint - docker

The packrat directory contains the source code for all the packages the project we depend on. If all works well, these will be installed on your computer when you open `PROJECTNAME.Rproj` in RStudio.

The checkpoint (TODO)

The Docker image includes all the necessary software, code and data to run our analysis. The Docker image may give a quicker entry point to the project, and is more self-contained, so might save some fiddling with installing things.

### Licenses

Some licences - [CC-BY-4.0](http://creativecommons.org/licenses/by/4.0/) - [MIT](http://opensource.org/licenses/MIT) year: 2017, copyright holder: Gionata Ghiggi - [CC-0](http://creativecommons.org/publicdomain/zero/1.0/) attribution requested in reuse

### Links and Acknowledgments

Project Template is inspired from: \* Carl Boettiger and his [template package](https://github.com/cboettig/template) \* Jeff Hollister and his [manuscriptPackage](https://github.com/jhollist/manuscriptPackage) \* Francisco Rodriguez-Sanchez's [template](https://github.com/Pakillo/template) \* Ben Mawerick [template](https://github.com/benmarwick/researchcompendium) \* Christopher Gandrud [Reproducible Research with R & RStudio, 2nd Edition](https://github.com/christophergandrud/Rep-Res-Book) \* [Reproducible Science Curriculum](https://github.com/Reproducible-Science-Curriculum/rr-init) \* ROpenSci [Reproducibility Guide](http://ropensci.github.io/reproducibility-guide/) \* Hadley Wickham [R Package Book](http://r-pkgs.had.co.nz/) \* Yihui Xie [Knitr package](http://yihui.name/knitr/) \* [RStudio](https://www.rstudio.com/)

### Contact

Gionata Ghiggi IACETHZ, Zurich <gionata.ghiggi@gmail.com>