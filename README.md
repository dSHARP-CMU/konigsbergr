
<!-- README.md is generated from README.Rmd. Please edit that file -->

# konigsbergr

[![Travis build
status](https://travis-ci.org/dSHARP-CMU/konigsbergr.svg?branch=master)](https://travis-ci.org/dSHARP-CMU/konigsbergr)
[![AppVeyor build
status](https://ci.appveyor.com/api/projects/status/github/dSHARP-CMU/konigsbergr?branch=master&svg=true)](https://ci.appveyor.com/project/dSHARP-CMU/konigsbergr)
[![Coverage
status](https://codecov.io/gh/dSHARP-CMU/konigsbergr/branch/master/graph/badge.svg)](https://codecov.io/github/dSHARP-CMU/konigsbergr?branch=master)

The goal of konigsbergr is to recreate the [“Bridges of
Königsberg”](https://en.wikipedia.org/wiki/Seven_Bridges_of_K%C3%B6nigsberg)
problem over any city by converting data from OpenStreetMap into a graph
and traversing it.

## Installation

You can install the development version:

``` r
devtools::install_github("dSHARP-CMU/konigsbergr")
```

## Usage

Konigsbergr works with OSM data, transforming it into a graph object and
then using the [pathfinder](https://github.com/dSHARP-CMU/pathfinder/)
package to traverse edges within it. The result is a pathway that will
try to cross all the bridges in a given city.

For the complete manual, see [the package
vignette](https://dsharp-cmu.github.io/konigsbergr/articles/konigsbergr.html).

## Context

This package is one of several originally developed by [Matthew
Lincoln](https:://github.com/mdlincoln) for use by Carnegie Mellon
University’s [“Bridges of Pittsburgh”](http://bridgesofpittsburgh.net/)
project:

  - [konigsberger](https://dsharp-cmu.github.io/konigsbergr/index.html)
    (end-user package)
      - [pathfinder](https://github.com/dSHARP-CMU/pathfinder/)
      - [bigosm](https://github.com/dSHARP-CMU/bigosm)
      - [simplygraph](https://github.com/dSHARP-CMU/simplygraph)
