## Introduction to R

### Dependencies

This repository contains introductory R material in the from of an R Notebook.
R Notebooks are R Markdown documents which allow users to run code interactively
from the markdown source.  This format requires a new version of the `rmarkdown`
package, and RStudio version 1.0.44 or higher.  RStudio can be downloaded from:

[Download RStudio](https://www.rstudio.com/products/rstudio/download3/)

And for further details about R Notebooks, see:

[R Notebooks](http://rmarkdown.rstudio.com/r_notebooks.html)

In addition, the material makes use of the following packages (and, of course,
all of the packages on which these depend):

* `dplyr`
* `ggplot2`
* `reshape2`
* `plotly`
* `highcharter`
* `sp`
* `maps`
* `leaflet`
* `DT`
* `shiny`
* `rbenchmark`

These can be installed all at once via:

```r
install.packages(c('rmarkdown', 'dplyr', 'ggplot2', 'reshape2', 'plotly',
                   'highcharter', 'sp', 'maps', 'leaflet', 'DT', 'shiny',
                   'rbenchmark'))
```

### Using the Material

This repository is created as an RStudio Project.  Either clone this repository,
or download as a zip and unpack it.  When done, browse to the folder in RStudio
and click on the `rintro.Rproj` file to open the project.  Once the project is
open, simply open the two markdown files `rintro.Rmd` and
`rintro_solutions.Rmd`.  The first is the main document, the second contains
solutions to exercises.
