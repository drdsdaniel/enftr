
<!-- README.md is generated from README.Rmd. Please edit that file -->

# enftr

<!-- badges: start -->

[![R build
status](https://github.com/endomer/enftr/workflows/R-CMD-check/badge.svg)](https://github.com/endomer/enftr/actions)
[![Lifecycle:
experimental](https://img.shields.io/badge/lifecycle-experimental-orange.svg)](https://www.tidyverse.org/lifecycle/#experimental)
[![CRAN
status](https://www.r-pkg.org/badges/version/enftr)](https://CRAN.R-project.org/package=enftr)
[![Codecov test
coverage](https://codecov.io/gh/drdsdaniel/enftr/branch/main/graph/badge.svg)](https://codecov.io/gh/drdsdaniel/enftr?branch=main)
<!-- badges: end -->

enftr es una interfaz para trabajar con la base de datos de la Encuesta
Nacional (tradicional) de Fuerza de Trabajo (ENFT) en R.

## Instalación

enftr aun no está en CRAN.

<!-- You can install the released version of encftr from [CRAN](https://CRAN.R-project.org) with: -->
<!-- ``` r -->
<!-- install.packages("encftr") -->
<!-- ``` -->

Pero puedes intalar la versión de desarrollo desde
[GitHub](https://github.com/) con:

``` r
tryCatch(
  library(remotes),
  error = function(e){
    install.packages('remotes')
  }
)
remotes::install_github("endomer/enftr")
```

## Contribuye

Tienes comentarios o quieres contribuir?

Por favor, revisa las [gias de contribución (en
inglés)](https://endomer.github.io/enftr/CONTRIBUTING.html) antes de
iniciar un issue o pull request.

Por favor, observa que el proyecto enftr está sujeto a un [Código del
contribuyente](https://contributor-covenant.org/es/version/2/0/CODE_OF_CONDUCT.html).
Contribuyendo con el proyecto aceptas las términos y condiciones.