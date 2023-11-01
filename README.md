# MSc Course: Introduction to data visualisation with ggplot2

This repository contains a tutorial on data visualisation using `ggplot2` for the Professional Skills in Ecology and Evolution module in the MSc Ecology, Evolution and Biodiversity at the University of Edinburgh.

This practical covers:

* Why use ggplot2?
* Histograms
* Scatterplots
* Boxplots
* Stats and customisations.

To run the practical, run the following code in your RStudio console:

```
library(remotes)
install_github("susjoh/MScDataVisualisation")
library("MScDataVisualisation")
learnr::run_tutorial("MSc_Data_Vis", package = "MScDataVisualisation")

```

If the last line throws an error, try this version:

```
learnr::run_tutorial("MSc_Data_Vis_v2", package = "MScDataVisualisation")
```


Alternatively, you can access the tutorial at https://susjoh.shinyapps.io/MSc_Data_Visualisation
