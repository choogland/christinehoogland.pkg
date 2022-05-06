
<!-- README.md is generated from README.Rmd. Please edit that file -->

# christinehoogland

<!-- badges: start -->
<!-- badges: end -->

The goal of christinehoogland is to practice package creation

## Installation

You can install the development version of christinehoogland from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("choogland/christinehoogland.pkg")
```

or locally with:

``` r
remotes::install_local(path = 'christinehoogland_0.0.0.9000.tar.gz')
```

# Function bmi

This function returns the Body Mass Index of an individual
(<https://en.wikipedia.org/wiki/Body_mass_index>).

The function must take 2 parameters, the mass in kg and the height in
meter. It returns the result of the operation mass/(height \* height).

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
