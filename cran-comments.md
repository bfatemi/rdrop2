Cran maintainers write:

We get

* checking for hidden files and directories ... NOTE
Found the following hidden files and directories:
  tests/testthat/.httr-oauth
These were most likely included in error. See section ‘Package
structure’ in the ‘Writing R Extensions’ manual.

* checking R code for possible problems ... NOTE
drop_read_csv: no visible global function definition for ‘read.csv’
Undefined global functions or variables:
  read.csv


Both issues are fixed in this submission.  