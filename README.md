
# flightscanner <img src='man/figures/logo.png' align="right" height="120" />

[![996.icu](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu)
[![License: GPL
v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Travis build
status](https://travis-ci.org/MinZhang95/flightscanner.svg?branch=master)](https://travis-ci.org/MinZhang95/flightscanner)
[![Coverage
status](https://codecov.io/gh/MinZhang95/flightscanner/branch/master/graph/badge.svg)](https://codecov.io/github/MinZhang95/flightscanner?branch=master)
[![HitCount](http://hits.dwyl.io/MinZhang95/flightscanner.svg)](http://hits.dwyl.io/MinZhang95/flightscanner)

## Topic

Web scraping/crawling flight information from SkyScanner API.
(<https://www.skyscanner.com/>). Keeping track of flight price will help
us choose best flights and save money without spending too much time on
searching.

## Website

<https://minzhang95.github.io/flightscanner/>

## Main Function

Given departure, destination and a range of acceptable departure date,

  - scrape flight information every day or every several hours.
  - filter flights by user-provided constraints such as price, duration,
    number of stops, etc.
  - visualize flight information by shiny.

Useful information may include *Price*, *Duration*, *Departure Time*,
*Arrival Time*, *Stops*, *Layover*, *Airline*, Flight Number, Class,
etc.

## Installation

You can install the released version of flightscanner from
[CRAN](https://CRAN.R-project.org) with:

``` r
devtools::install_github("MinZhang95/flightscanner")
```

## Example
