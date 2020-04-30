
# Notes on *Statistical Rethinking: A Bayesian Course with Examples in R and Stan*

The first two chapters of the 2nd edition of this book are available as
a [PDF](statisticalrethinking2_chapters1and2.pdf) for free. The rest of
the book I used the first edition as it is available through my schools
library.

## Introduction

This book is an introduction to Bayesian statistics, focussing on
providing an applicable education in R. This reporisoty contains my
notes; these notes are not a throughough recapitulation of the book, but
instead acting as a combination of a reference and a playground for
myself.

## Setting-up

This course includes an R packages called ‘rethinking’\](). It can be
installed as follows.

``` r
# Dependencies
install.packages(c("coda", "mvtnorm", "devtools", "loo", "dagitty"))

# Course package
devtools::install_github("rmcelreath/rethinking")
```

## Notes

[Chapter 1. The Golem of Prague](ch1_the-golem-of-prague.md)

[Chapter 2. Small Worlds and Large
Worlds](ch2_small-worlds-and-large-worlds.md)

[Chapter 3. Sampling the Imaginary](ch3_sampling-the-imaginary.md)

[Chapter 4. Linear Models](ch4_linear-models.md)
