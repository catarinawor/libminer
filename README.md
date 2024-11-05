
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->
<!-- badges: end -->

The goal of libminer is to …

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("catarinawor/libminer")
```

## Example usage

To get a count of installed packages in each of your library locations,
optionally with the total sizes, use the `lib_summary()` function:

``` r
library(libminer)
lib_summary()
#>                                                                  Library
#> 1                 C:/Users/worc/AppData/Local/Programs/R/R-4.4.0/library
#> 2 C:/Users/worc/AppData/Local/Temp/1/RtmpMTQTte/temp_libpath693c6f0f643d
#> 3                                       C:/Users/worc/Documents/Rlib/4.4
#>   n_packages
#> 1         61
#> 2          1
#> 3        267
```

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub and CRAN.
