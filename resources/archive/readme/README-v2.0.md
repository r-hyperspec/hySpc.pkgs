# Download **`r-hyperspec`** Family Packages

Welcome!

This is a repository holding certain R packages in the [**`r-hyperspec`**](https://r-hyperspec.github.io/) series (in particular, data-rich packages that are too large to be distributed on CRAN).

**For developers:** The instructions about how to administer this repo are in [`CONTRIBUTING.md`](https://github.com/r-hyperspec/pkg-repo/blob/gh-pages/CONTRIBUTING.md).

**For users:** If you want to install a package, simply use R function `install.packages()` with the additional repository added as shown in this example:

```r
repos <- c("https://r-hyperspec.github.io/pkg-repo/", getOption("repos"))
install.packages("hyperSpec", repos = repos)
```

Instead of `"hyperSpec"`, you may use any name of a package that resides in this repository or on [CRAN](https://cran.rstudio.com/web/packages/index.html).
You may also use a vector of several package names.


<!-- list of packages: start | DO NOT REMOVE THIS LINE -->
