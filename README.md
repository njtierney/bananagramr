
<!-- README.md is generated from README.Rmd. Please edit that file -->
bananagramr
===========

The goal of bananagramr is to explore whether our bags of bananagrams would have been fine if we just randomly split them.

installing bananagramr
======================

``` r

#install.packages("devtools")

devtools::install_github("njtierney/bananagramr")
```

The story
---------

I was at a party and we combined two packets of bananagrams to play a big game, but then when we came to putting them back together we wanted to just randomly split them. I understood that this should be fine, but I wanted to be sure. Naturally, everyone was super thrilled when I demanded that we count up all the tiles and record the number in each letter for each of the randomly chosen tiles.

I promised my friends that I'd write about this process, and I like writing R packages as analyses, so this seemed like a good idea. The data can be accessed using

``` r
library(bananagramr)

dat_bananagram
#> # A tibble: 26 × 3
#>    letter bag_1 bag_2
#>     <chr> <dbl> <dbl>
#> 1       A    11    15
#> 2       B     5     1
#> 3       C     2     4
#> 4       D     6     6
#> 5       E    18    18
#> 6       F     4     4
#> 7       G     4     4
#> 8       H     1     1
#> 9       I    15    15
#> 10      J     2     2
#> # ... with 16 more rows
```
