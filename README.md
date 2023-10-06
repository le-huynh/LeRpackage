
<!-- README.md is generated from README.Rmd. Please edit that file -->
# lehuynh

<!-- badges: start -->
<!-- badges: end -->
This package includes R codes that are useful to me.

## Installation

`lehuynh` R package can be installed from GitHub with:

``` r
devtools::install_github("le-huynh/lehuynh")
```

### Functions
- `ggsave_elsevier( )`: Save a plot using `ggplot2::ggsave( )`. Plot size follows instructions of Elsevier journals.
- `import_data( )`: Import multiple .csv or .rds objects. The output is a *named* list of imported objects or separate objects in the .GlobalEnv.
- `import_excel( )`: Import excel file with multiple sheets. The output is a *named* list of imported sheets or separate dataframes in the .GlobalEnv. 
- `lehuynh_theme( )`: Personal ggplot2 theme: white background, black axis, black text
- `MinMaxScaling( )`: min-max normalization (min = 0, max = 1)
- `new_project( )`: Create a [project](https://github.com/SchlossLab/new_project) for reproducible purpose
- `ppc_brms( )`
- `tidytuesday( )`: Create a new folder for [#tidytuesday](https://github.com/rfordatascience/tidytuesday) challenge
- `tsi( )`: Calculate TSI (Trophic state index) [(Carlson, 1977)](https://doi.org/10.4319/lo.1977.22.2.0361)

### Templates
- `draft_elsevier`: creating an Rmarkdown manuscript for Elsevier journals [(example)](https://github.com/le-huynh/writing_journal_article_in_rmarkdown/tree/master/elsevier)
- `lehuynh_Bayes_brms`: Basic steps to fit, check, and interpret a Bayesian model via `brms` package
- `lehuynh_EA`: Basic steps to do Exploratory Analysis
