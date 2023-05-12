
<!-- README.md is generated from README.Rmd. Please edit that file -->

# BPrinStratTTE

<!-- badges: start -->

[![](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://lifecycle.r-lib.org/articles/stages.html#experimental)
<!-- badges: end -->

Bayesian principal stratification for exponentially distributed
time-to-event endpoints to explore potential immunogenicity effects in
clinical trials of biologics.

## Scope

- The package contains functions to fit Bayesian principal
  stratification models and to perform clinical trial simulations in
  order to determine operating characteristics for given scenarios.
- Two-arm clinical trials of biologics are considered
  - with an intercurrent event (determining the principal stratum of
    interest) that can only occur in the treated arm (such as the
    occurence of antidrug antibodies), and
  - with time-to-event endpoint that is assumed to follow an exponential
    distribution.
- Potential predictors of the intercurrent event can be taken into
  account.

## Installation

You can install the `BPrinStratTTE` package from GitHub with:

``` r
if (!require("remotes")) {install.packages("remotes")}
remotes::install_github("chstock/BPrinStratTTE")
```
