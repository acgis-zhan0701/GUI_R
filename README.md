## Project 

National Ecological Framework Attribute Calculator V 0.1

### Description

This NEF (National Ecological Framework) Attribute Calculator is a web application created in R and R shiny packages.


### R packages

This web application required one package and one optional package.

1. shiny. Shiny is a necessary R package to create web apps in R in this project.
2. shinythemes. Shinythemes is an optional R package that used for create different layout of shiny web applcation.

### Global Variables

GIS datasets for the different level of ecological zone. GIS dataset is produced by CanSIS, https://sis.agr.gc.ca/cansis/nsdb/ecostrat/gis_data.html
	- "Ecozone_shp.zip"
	- "Ecoprovince_shp.zip"
	- "Ecoregion_shp.zip"
	- "Ecodistrict_shp.zip"

### Output File

Output attribute table will present in the output panel. Click download button to download the result as .dbf database format.

"XX_elevation"
(ex: "zn_elevation.dbf")


### Elevation Calculator

I used my [elevation](https://github.com/acgis-zhan0701/testreadme) R code to create this elevation calculator.

### Soil Great Group


Estimate processing time can depend on which framework layer that you are choosing.
For ecozone, estimate processing time is 10 hour.
For ecoprovince, estimate processing time is 7 hour.
For ecoregion, esitimate processing time is 5 hour.
For ecodistrict, estimate processing time is 3 hour.