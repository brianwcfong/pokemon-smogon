## Pokemon Smogon Tier List - EDA and Tier Placement Predictions for Gen 7 Pokemon

### Abstract
This directory is a work in progress containing data exploration of data scraped from the [Smogon University](http://www.smogon.com/dex/sm/pokemon/) in Aug 2017 and explores the data to find relationships between a Pokemon's stats, moves and other factors and their placement in the Smogon Tier List. The goal is to create classification models that can predict which Tier (e.g. Uber, OU, UU, RU, NU) new Pokemon belong to.

### Data Sources
* Data was scraped from the Page Source of [Smogon's Gen SM Pokedex](http://www.smogon.com/dex/sm/pokemon/), which contains all Pokemon/Moves/Items from Gen 1-7 in JSON format. Additional sources were found online and used to supplement the Smogon data. These files are included as CSV in the directory.

### Dependencies
R Version 3.4.0 was used, along with the following libraries:
```
library(tidyverse)
library(ggthemes)
library(knitr)
library(mlr)
library(RColorBrewer)
library(jsonlite)
library(data.table)
```
![alt text](./pokemon.csv "Sample Data")

### Author
* Brian Fong
brian.fong@thinkbiganalytics.com

### License
* This repository is under the GPL V3 license

### Built With
* R Version 3.4.0 with RStudio
