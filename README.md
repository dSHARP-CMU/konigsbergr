
<!-- README.md is generated from README.Rmd. Please edit that file -->

# konigsbergr

[![Travis build
status](https://travis-ci.org/dSHARP-CMU/konigsbergr.svg?branch=master)](https://travis-ci.org/dSHARP-CMU/konigsbergr)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/dSHARP-CMU/konigsbergr?branch=master&svg=true)](https://ci.appveyor.com/project/dSHARP-CMU/konigsbergr)
[![Coverage
status](https://codecov.io/gh/dSHARP-CMU/konigsbergr/branch/master/graph/badge.svg)](https://codecov.io/github/dSHARP-CMU/konigsbergr?branch=master)

The goal of konigsbergr is to recreate the “Bridges of Königsberg”
problem over any city by converting data from OpenStreetMap into a graph
and traversing it.

## Installation

You can install the development version:

``` r
devtools::install_github("dSHARP-CMU/konigsbergr")
```

## Usage

Get OSM data

Project it into a graph and identify bridge attributes - subset for
roads - subset for pedestrians - subset for custom

Run “pathfinder”

Visualize with SF/leaflet
