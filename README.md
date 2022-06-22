# sigident.func (!!! currently under development !!!)

<!-- badges: start -->
[![R CMD Check via {tic}](https://github.com/kapsner/sigident.func/workflows/R%20CMD%20Check%20via%20{tic}/badge.svg?branch=master)](https://github.com/kapsner/sigident.func/actions)
[![linting](https://github.com/kapsner/sigident.func/workflows/lint/badge.svg?branch=master)](https://github.com/kapsner/sigident.func/actions)
[![test-coverage](https://github.com/kapsner/sigident.func/workflows/test-coverage/badge.svg?branch=master)](https://github.com/kapsner/sigident.func/actions)
[![codecov](https://codecov.io/gh/kapsner/sigident.func/branch/master/graph/badge.svg)](https://codecov.io/gh/kapsner/sigident.func)
<!-- badges: end -->

This is the repository of the R package `sigident.func`. It provides functional analysis and is part of the `sigident` package framework: [https://github.com/kapsner/sigident](https://github.com/mikapsner/sigident)

# Overview 

The functional analysis includes the following steps:  
* DEG analysis  
* Gene enrichment  
* Test for over-representation  
* GO enrichment analysis

# Installation

You can install *sigident.func* with the following commands in R:

``` r
install.packages("remotes")
remotes::install_github("kapsner/sigident.func")
```

# Example

Please study the [package's vignette](vignettes/) for a detailed example. 

Since the building the package vignette takes rather long (~ 20 min.), we provide the already built vignettes in [this repository](https://github.com/miracum/clearly-sigident_vignettes). 

# Notice 

The *sigident.func* package is under active development and not on CRAN yet - this means, that from time to time, the API can break, due to extending and modifying its functionality. It can also happen, that previoulsy included functions and/or function arguments are no longer supported. 
However, a detailed package vignette will be provided alongside with every major change in order to describe the currently supported workflow.

# More Infos:

- about CLEARLY: [https://www.transcanfp7.eu/index.php/abstract/clearly.html](https://www.transcanfp7.eu/index.php/abstract/clearly.html)
- about MIRACUM: [https://www.miracum.org/](https://www.miracum.org/)
- about the Medical Informatics Initiative: [https://www.medizininformatik-initiative.de/index.php/de](https://www.medizininformatik-initiative.de/index.php/de)
