
<!-- README.md is generated from README.Rmd. Please edit that file -->

# checkhelper

A package to help you deal with devtools::check outputs

## Examples

Check the package and get the globals missing

``` r
# Get globals
globals <- get_no_visible()
globals

# Print globals to copy-paste
print_globals(globals)
# Store in package using usethis::use_r("globals")
```

Please note that this project is released with a [Contributor Code of
Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree
to abide by its terms.
