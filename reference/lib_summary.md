# R Library Summary

Provides a brief summary of the package libraries on your machine

## Usage

``` r
lib_summary(sizes = FALSE)
```

## Value

A `data.frame` containing the count of packages in each of the user's
libraries

## Examples

``` r
lib_summary()
#>                                   Library n_packages
#> 1         /home/runner/work/_temp/Library         55
#> 2              /opt/R/4.6.1/lib/R/library         29
#> 3 /tmp/Rtmp6Oc4OK/temp_libpath189cf8e3297          1
lib_summary(sizes = TRUE)
#>                                   Library n_packages lib_size
#> 1         /home/runner/work/_temp/Library         55   68.22M
#> 2              /opt/R/4.6.1/lib/R/library         29   73.56M
#> 3 /tmp/Rtmp6Oc4OK/temp_libpath189cf8e3297          1   35.89K
```
