## RcppGetconf [![Build Status](https://travis-ci.org/eddelbuettel/rcppgetconf.svg)](https://travis-ci.org/eddelbuettel/rcppgetconf) [![License](http://img.shields.io/badge/license-GPL%20%28%3E=%202%29-brightgreen.svg?style=flat)](http://www.gnu.org/licenses/gpl-2.0.html) [![CRAN](http://www.r-pkg.org/badges/version/RcppGetconf)](http://cran.r-project.org/package=RcppGetconf) [![Downloads](http://cranlogs.r-pkg.org/badges/RcppGetconfcolor=brightgreen)](http://www.r-pkg.org/pkg/RcppGetconf)

Rcpp Read Access to System Configuration Settings

### What is this?

Modern POSIX system have a binary `getconf` which can access the system
calls `sysconf`, `pathconf` and `confstr`.  This package brings the
values back to R.

### Requirements

This package requires access to these system calls, and definitions of
its data structures in the system header files.  We have used it
exclusively on Linux so far.  It _should_ work on OS X, and contributions
would be very welcome.

### Status

It builds and provides so far a single function `getAll()`. It may go to
[CRAN](https://cran.r-project.org/package=RcppGetconf) in its current
form as it builds cleanly.

### Author

Dirk Eddelbuettel

### License

GPL (>= 2)