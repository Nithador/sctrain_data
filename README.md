# Data used in HPC in Data Science: focus on Big Data and AI training

This repository contains data used in the training called HPC in Data Science: focus on Big Data and AI training.

Originally these datasets are taken from R and stored as CSVs.

## Airquality dataset

Daily air quality measurements in New York, May to September 1973. Bundled with R base package and callable by `airquality` command.

According to R documentation:
### Source
The data were obtained from the New York State Department of Conservation (ozone data) and the National Weather Service (meteorological data).

### References
Chambers, J. M., Cleveland, W. S., Kleiner, B. and Tukey, P. A. (1983) Graphical Methods for Data Analysis. Belmont, CA: Wadsworth.

## Ames dataset

A data set from De Cock (2011) has 82 fields were recorded for 2,930 properties in Ames IA. This version is copies from the AmesHousing package but does not include a few quality columns that appear to be outcomes rather than predictors. Part of the `modeldata` package and calleable by `modeldata::ames` command.

According to R documentation:
### Source
http://jse.amstat.org/v19n3/decock/DataDocumentation.txt

http://jse.amstat.org/v19n3/decock.pdf

### References
De Cock, D. (2011). "Ames, Iowa: Alternative to the Boston Housing Data as an End of Semester Regression Project," Journal of Statistics Education, Volume 19, Number 3.

## Credit data dataset

These data are from the website of Dr. Lluís A. Belanche Muñoz by way of a github repository of Dr. Gaston Sanchez. One data point is a missing outcome was removed from the original data.. Part of the `modeldata` package and calleable by `modeldata::credit_data` command.

According to R documentation:
### Source
https://github.com/gastonstat/CreditScoring, http://bit.ly/2kkBFrk

## Iris dataset

This famous (Fisher's or Anderson's) iris data set gives the measurements in centimeters of the variables sepal length and width and petal length and width, respectively, for 50 flowers from each of 3 species of iris. The species are Iris setosa, versicolor, and virginica. Bundled with R base package and callable by `iris` command.

According to R documentation:
### Source
Fisher, R. A. (1936) The use of multiple measurements in taxonomic problems. Annals of Eugenics, 7, Part II, 179–188.

The data were collected by Anderson, Edgar (1935). The irises of the Gaspe Peninsula, Bulletin of the American Iris Society, 59, 2–5.

### References
Becker, R. A., Chambers, J. M. and Wilks, A. R. (1988) The New S Language. Wadsworth & Brooks/Cole. (has iris3 as iris.)

## Risk factors dataset

The data is a subset of the 2009 survey from BRFSS, an ongoing data collection program designed to measure behavioral risk factors for the adult population (18 years of age or older) living in households. Part of the `naniar` package and calleable by `naniar::riskfactors` command.

According to R documentation:
### Source
https://www.cdc.gov/brfss/annual_data/annual_2009.htm

## Star Wars dataset

The original data, from SWAPI, the Star Wars API, https://swapi.dev/, has been revised to reflect additional research into gender and sex determinations of characters.. Part of the `dplyr` package and calleable by `dplyr::starwars` command.
