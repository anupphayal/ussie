
<!-- README.md is generated from README.Rmd. Please edit that file -->

# ussie

<!-- badges: start -->

[![R-CMD-check](https://github.com/anupphayal/ussie/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/anupphayal/ussie/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

The goal of ussie is to use EU soccer leGUE data BY THE
**ENGSOCCERDATA**

## Installation

You can install the development version of ussie from
[GitHub](https://github.com/) with:

``` r
# install.packages("devtools")
devtools::install_github("anupphayal/ussie")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
library(ussie)
## basic example code to get Spanish league
uss_make_matches(engsoccerdata::spain, "Spain")
#> # A tibble: 23,915 × 8
#>    country tier  season date       home         visitor goals_home goals_visitor
#>    <chr>   <fct>  <int> <date>     <chr>        <chr>        <int>         <int>
#>  1 Spain   1       1928 1929-02-10 Arenas de G… Atleti…          2             3
#>  2 Spain   1       1928 1929-02-10 Espanyol Ba… Real U…          3             2
#>  3 Spain   1       1928 1929-02-10 Real Madrid  CE Eur…          5             0
#>  4 Spain   1       1928 1929-02-10 Real Socied… Athlet…          1             1
#>  5 Spain   1       1928 1929-02-12 Racing Sant… FC Bar…          0             2
#>  6 Spain   1       1928 1929-02-17 FC Barcelona Real M…          1             2
#>  7 Spain   1       1928 1929-02-17 Athletic Bi… Espany…          9             0
#>  8 Spain   1       1928 1929-02-17 Atletico Ma… Real S…          0             3
#>  9 Spain   1       1928 1929-02-17 Real Union   Racing…          3             1
#> 10 Spain   1       1928 1929-02-17 CE Europa    Arenas…          5             2
#> # … with 23,905 more rows
```
