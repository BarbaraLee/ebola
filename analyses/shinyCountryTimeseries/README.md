The app can also be viewed online by visiting:
https://chendaniely.shinyapps.io/shinyCountryTimeseries/

The app requires the following R packages to be installed: RCurl, foreign,
ggplot2, stringr, reshape2, magrittr, dplyr, scales, shiny

It can be installed in R via:

`install.packages(c("RCurl", "foreign", "ggplot2", "stringr", "reshape2", "magrittr", "dplyr", "scales", "shiny"))`

To run this application locally, browse to the parent directory of where the
ui.R and server.R scripts, open up R such that the `getwd()` is the
parent directory. Then load shiny, by using `library(shiny)` and then
launch the application by typing `runApp("shiny-country-timeseries")`

TODO
====
I have a few ideas on how to build out the plot further:

* Overlay R0 curves over the cases plots
  * Give sliders to adjust initial number of cases and R0

* Overlay other pandemic curves in cases/deaths for comparison

Additional suggestions and datasets welcome!
