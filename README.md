
<!-- README.md is generated from README.Rmd. Please edit that file -->

# gendercodeR

The goal of gendercodeR is to allow simple recoding of freetext gender
responses.

## Why would we do this?

Researchers who collect self-reported demographic data from respondents
occasionally collect gender using a free-text response option. This has
the advantage of respecting the gender diversity of respondents.
However, this presents a challenge to researchers in that some
inconsistencies in typography and spelling create a larger set of
responses than would be required to fully capture the demographic
characteristics of the sample.

For example, male participants may provide freetext responses as “male”,
“man”, “mail”, “mael”. Non-binary participants may provide responses as
“nonbinary”, “enby”, “non-binary”, “non binary”

This package uses dictionaries of common mispellings to recode these
freetext responses into a consistent set of responses.

## Installation

You can install the released version of gendercodeR from
[CRAN](https://CRAN.R-project.org) with:

``` r
install.packages("gendercodeR")
```

## Example

This is a basic example which shows you how to solve a common problem:

``` r
## basic example code
```

What is special about using `README.Rmd` instead of just `README.md`?
You can include R chunks like so:

``` r
summary(cars)
#>      speed           dist       
#>  Min.   : 4.0   Min.   :  2.00  
#>  1st Qu.:12.0   1st Qu.: 26.00  
#>  Median :15.0   Median : 36.00  
#>  Mean   :15.4   Mean   : 42.98  
#>  3rd Qu.:19.0   3rd Qu.: 56.00  
#>  Max.   :25.0   Max.   :120.00
```

You’ll still need to render `README.Rmd` regularly, to keep `README.md`
up-to-date.

You can also embed plots, for example:

<img src="man/figures/README-pressure-1.png" width="100%" />

In that case, don’t forget to commit and push the resulting figure
files, so they display on GitHub\!