# csvgen

[![codecov](https://codecov.io/gh/joppich/csvgen/branch/master/graph/badge.svg)](https://codecov.io/gh/joppich/csvgen)
[![Build Status](https://travis-ci.com/joppich/csvgen.svg?branch=travis)](https://travis-ci.com/joppich/csvgen)

a small utility to create mock-csv files with various datatypes.

## commandline parameters

All commandline parameters are optional.

- __size__: required filesize

  default: _2 MB_
- __header__: create column headers

  default: _string, float, int_
- __column-types__: pass types for column values

  default: _string, float, int_
- __filepath__: write to provided path

  default: _stdout_
