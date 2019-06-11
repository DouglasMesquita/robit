
# FLAMES

<!-- badges: start -->

<!-- [![CRAN status](https://www.r-pkg.org/badges/version/FLAMES)](https://cran.r-project.org/package=FLAMES) -->

[![Travis build
status](https://travis-ci.org/DouglasMesquita/FLAMES.svg?branch=master)](https://travis-ci.org/DouglasMesquita/FLAMES)
<!-- [![Codecov test coverage](https://codecov.io/gh/DouglasMesquita/FLAMES/branch/master/graph/badge.svg)](https://codecov.io/gh/DouglasMesquita/FLAMES?branch=master) -->
<!-- badges: end -->

## Overview

FLAMES: Flexible Link function with AssyMptotES is a package able to fit
binary regression under several link functions and two possible
assymptotes parameters, c and d, in the form

\[p_i = c + (d-c)F_v(\text{X}\beta)\]

## Installation

``` r
# Install from CRAN (when available)
install.packages("FLAMES")
# Or the development version from GitHub
# install.packages("devtools")
devtools::install_github("DouglasMesquita/FLAMES")
```

## Usage

`library(FLAMES)` will load **mcmc\_bin**, a function to fit binary
regression models. The user can choose for MCMC based on ARMS or
Metropolis Hastings algorithms. Also it is possible to fit **logit**,
**probit**, **cauchit**, **cloglog**, **loglog** and **robit**
regressions.

See `?mcmc_bin` for examples.
