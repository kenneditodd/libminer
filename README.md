
<!-- README.md is generated from README.Rmd. Please edit that file -->

# libminer

<!-- badges: start -->
<!-- badges: end -->

The goal of libminer is to provide an overview of your R library setup.
It is a toy package created as a part of a workshop and not meant for
serious use.

## Installation

You can install the development version of libminer from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("kenneditodd/libminer")
```

## Example

To get a count of installed packages in each of your libaries,
optionally iwth the total sizes, use `lib_summary()`.

``` r
library(libminer)

lib_summary()
#>                                                                                       Library
#> 1                              /Library/Frameworks/R.framework/Versions/4.2/Resources/library
#> 2 /private/var/folders/2p/xrsx4gc16g1056vc8nwhth0c_vq37m/T/RtmpggRczF/temp_libpath4cedcbf859e
#>   n_packages
#> 1        308
#> 2          1
lib_summary(sizes = TRUE)
#>                                                                                       Library
#> 1                              /Library/Frameworks/R.framework/Versions/4.2/Resources/library
#> 2 /private/var/folders/2p/xrsx4gc16g1056vc8nwhth0c_vq37m/T/RtmpggRczF/temp_libpath4cedcbf859e
#>   n_packages   lib_size
#> 1        308 1740893113
#> 2          1      14307
```
