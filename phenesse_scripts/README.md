# Code for: Citizen science supports ecological predictions of phenology in North American mimetic butterflies 

**DATA CITATION:** iNaturalist contributors, iNaturalist (2025). iNaturalist Research-grade Observations. iNaturalist.org. Occurrence dataset https://doi.org/10.15468/ab3s5x accessed via GBIF.org on 2025-03-19.


**phenesse_scripts:** This folder contains all scripts used to generate onset phenology estimates, perform two-sample z-tests, and generate figures. Scripts must be run in the order they are listed below.

*all analysis were performed using R version 4.4.1 (2024-06-14)*

**phenesse_estimates_GBIF.Rmd:** This script cleans the iNaturalist data and generates onset phenology estimates for all species, and populates the data frame titled "phenesse_estimates_df.csv" with these estimates. 

**phenesse_analysis.Rmd:** This script performs the statistical analysis for the onset phenology estimates, and generates the data frame titled "ztest_df.csv"

**GBIF_point_plots.Rmd:** This script generates point plots for all iNaturalist records of Battus philenor, Limenitis arthemis astyanax, Danuas plexippus, and Limenitis archippus, calculates total sample sizes of occurrence records, and visualizes geographic limits of the focal study with bounding boxes 

**phenology_plots.Rmd:** This script uses the phenesse_estimates_df.csv data frame to generate all plots presented in the manuscript. 

**PACKAGE VERSION INFORMATION:** 
> packageVersion("curl")
[1] ‘5.2.1’
> packageVersion("ggplot2")
[1] ‘3.5.1’
> packageVersion("tidyverse")
[1] ‘2.0.0’
> packageVersion("dplyr")
[1] ‘1.1.4’
> packageVersion("lubridate")
[1] ‘1.9.3’
> packageVersion("sf")
[1] ‘1.0.19’
> packageVersion("spData")
[1] ‘2.3.1’
> packageVersion("phenesse")
[1] ‘0.1.2’
> packageVersion("rgbif")
[1] ‘3.8.1’
> packageVersion("stringr")
[1] ‘1.5.1’
> packageVersion("ggpubr")
[1] ‘0.6.0’
> packageVersion("ggmap")
[1] ‘4.0.0’
> packageVersion("sp")
[1] ‘2.1.4’
> packageVersion("adehabitatHR")
[1] ‘0.4.21’
> packageVersion("maps")
[1] ‘3.4.2’
> packageVersion("patchwork")
[1] ‘1.2.0’
> packageVersion("gginnards")
[1] ‘0.2.0.1’
> packageVersion("tibble")
[1] ‘3.2.1’
> packageVersion("magrittr")
[1] ‘2.0.3’
> packageVersion("eseis")
[1] ‘0.8.1’