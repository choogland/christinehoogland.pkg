
<!-- README.md is generated from README.Rmd. Please edit that file -->

# christinehoogland

<!-- badges: start -->
<!-- badges: end -->

The goal of christinehoogland is to practice package creation

## Installation

You can install the development version of christinehoogland like so:

``` r
# install.packages("devtools")
devtools::install_github("choogland/christinehoogland")
```

## Function bmi

# This line works:

``` r
library(christinehoogland)

bmi(mass = 80, height = 1.80)
#> [1] 24.69136
bmi(mass = NA, height = 1.80)
#> [1] NA
bmi(mass = 80, height = NA)
#> [1] NA
bmi(mass = NA, height = NA)
#> [1] NA
```

## Code of Conduct

Please note that the christinehoogland project is released with a
[Contributor Code of
Conduct](https://contributor-covenant.org/version/2/0/CODE_OF_CONDUCT.html).
By contributing to this project, you agree to abide by its terms.
