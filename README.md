TStools 
=======

Collection of R functions for time series analysis

To install use:

> if (!require("devtools")){install.packages("devtools")}

> devtools::install_github("trnnick/TStools")

The package now depends on Rcpp and RcppArmadillo, which will be installed automatically.

However Mac OS users may need to install gfortran libraries in order to use Rcpp. Follow the link for the instructions: http://www.thecoatlessprofessor.com/programming/rcpp-rcpparmadillo-and-os-x-mavericks-lgfortran-and-lquadmath-error/

Note
-------
Functions es() and sim.ets() are now maintained and updated in "smooth" package: https://github.com/config-i1/smooth The versions provided in TStools will be supported but updated less frequently.
