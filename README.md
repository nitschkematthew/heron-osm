# Heron Island/Reef map in R

Produce a simple map of Heron Island and its surrounding reef using open source data from www.openstreetmap.org

### Required R packages

The map data is scraped from OSM using the R package osmdata which is an interface for the OSM api. The remaining packages are for plotting.

```
library("ggplot2")
library("sf")
library("osmdata")
library("ggspatial")
```