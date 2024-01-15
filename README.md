# ST2195 Assignment 4

This repository contains the code for ST2195 Assignment 4, a practice assignment for the Data Science and Business Analytics program at the University of London. The assignment involves debugging and revising a piece of R code that calculates the volumes of spheres with different radii.

## Assignment Details

The assignment involves the following steps:

1.  Commit and push the initial buggy code as a file called "foo.R".
2.  Find and fix all the bugs in the code. Each fixed bug is worth 1 point.
3.  Update "foo.R" by committing and pushing the revisions.

## Code Overview

The initial code provided in "foo.R" is intended to calculate the volumes of spheres with radii `r`, `r^2`, and `r^3`. However, it contains several bugs that prevent it from working correctly.

Here is the initial code:

``` r
# Radius
r <- 2

# Function to compute the volume of a sphere with radius r
volume <- function(r, rho) {
  3/4*pi*r^2
}

# Function to compute the volumes of the spheres with radius r, r^2 and r^3
volume_vector <- function(r) {
  r <- 22
  for (r in 2:4){
    volume(r)
  }
}

# Run volume_vector(r) and print the volumes of the spheres with radius r, r^2 and r^3
volume_vector(r)
```

### By: Yi-Jun Liu 🧑🏻‍💻
