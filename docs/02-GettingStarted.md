
# Getting started {#start}

To analyse light-level geolocator data in R we need a couple of R packages as well as functions that allow to run our code. We created a package called _GeoLocTools_ that contains functions that are not nessesarily associated to a certain package but are used in this manual. Importantly the package can also run a check on you system (function: _setupGeolocation()_), detecting packages that are already on your computer and installs the missing tools directly from CRAN or GitHub.

The package requires _devtools_ (install if nessesary using the _install.packages()_ function). With _devtools_ on your system, you are able to download and built as well as install R packages directly from GitHub (e.g. _GeoLocTools_).


```r
library(devtools)
install_github("SLisovski/GeoLocTools")
```

You should now be able to load the package and run the `setupGeolocation()` function. We recommend to include this line at the beginning of each script you create for a geolocator analysis. Also check (every now and then), if there is a new version of _GeoLocTools_ available. And if that is the case, re-install the package using the same code you used for initial installation.