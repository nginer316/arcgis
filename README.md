
<!-- README.md is generated from README.Rmd. Please edit that file -->

# arcgis

<!-- badges: start -->

[![R-CMD-check](https://github.com/R-ArcGIS/arcgis/actions/workflows/R-CMD-check.yaml/badge.svg)](https://github.com/R-ArcGIS/arcgis/actions/workflows/R-CMD-check.yaml)
<!-- badges: end -->

arcgis is a meta-package that loads ArcGIS location services packages
for R. It provides a comprehensive suite of tools for working with
ArcGIS Data and Location services for ArcGIS Online, ArcGIS Enterprise,
and Location Platform.

## Included Packages

This package installs and loads the following R-ArcGIS ecosystem
packages:

- **[{arcgisutils}](https://github.com/r-arcgis/arcgisutils)**:
  Developer-oriented utility functions providing the building blocks for
  R packages that work with ArcGIS Location Services. Handles
  authorization, Esri JSON construction and parsing, and geometry
  conversions.

- **[{arcgislayers}](https://github.com/r-arcgis/arcgislayers)**: The
  workhorse package for reading, writing, publishing, and managing
  vector and raster data via ArcGIS location services REST API
  endpoints. Works with ArcGIS Enterprise, ArcGIS Online, and ArcGIS
  Platform.

- **[{arcpbf}](https://github.com/r-arcgis/arcpbf)**: Fast processing of
  ArcGIS FeatureCollection protocol buffers in R. Designed to work
  seamlessly with httr2 and integrates with sf for spatial data
  workflows.

- **[{arcgisgeocode}](https://github.com/r-arcgis/arcgeocode)**: A
  robust interface to ArcGIS geocoding services. Provides capabilities
  for reverse geocoding, finding address candidates,
  character-by-character search autosuggestion, and batch geocoding.

- **[{calcite}](https://github.com/r-arcgis/calcite)**: Bindings to the
  Calcite Design System JavaScript component library. Enables creation
  of interactive web applications and static HTML using ArcGIS design
  patterns.

## Installation

Install the metapackage from cran with:

``` r
install.packages("arcgis")
```

You can install the development version of arcgis from
[GitHub](https://github.com/) with:

``` r
# install.packages("remotes")
remotes::install_github("R-ArcGIS/arcgis")
```

## Learn More

To learn more about the R-ArcGIS Bridge project, visit the [developer
site]((https://developers.arcgis.com/r-bridge))
