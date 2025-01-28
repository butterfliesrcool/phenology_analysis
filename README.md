# Code for: Citizen science supports ecological predictions of phenology in a butterfly mimicry complex

**ABSTRACT:** Phenological synchrony enables species to occur when conditions are optimal for survival. While phenological synchrony between butterflies and their host-plants has been extensively documented, the importance of phenology in maintaining interspecies interactions, such as mimicry, is less well understood. Batesian mimicry occurs when a palatable species (i.e., the mimic) evolves a phenotypic resemblance to an unpalatable, often defended, species (i.e., the model), resulting in protection against predation for the mimic. Theory predicts that models should emerge seasonally before their mimics to give predators sufficient time to learn, recognize and avoid their aposematic signal (i.e., model-first hypothesis). Here, we use citizen science data from iNaturalist to test these long-standing predictions. To understand the potential influences of mimicry and shared life history on the evolution of phenological strategies, we estimate onset phenology of Battus philenor, a toxic butterfly species, and Limenitis arthemis astyanax, its palatable mimic, along with Limenitis archippus, a close relative of L. a. astyanax. Our results support the model-first hypothesis and demonstrate that B. philenor emerges significantly before its Batesian mimic L. a. astyanax. This research highlights a new avenue for using large-scale citizen science datasets to address long-standing questions about how phenology impacts complex ecological interactions. 

**NAVIGATING R SCRIPTS:**

*all analysis were performed using R version 4.4.1 (2024-06-14)*

**point_plots:** This script generates point plots for iNaturalist data of Battus philenor, Limenitis arthemis astyanax, and Limenitis archippu and calculates sample sizes. 

**phenesse_estimates.Rmd:** This script cleans the iNaturalist data and generates onset phenology estimates for all species, and populates the data frame titled "phenesse_estimates_df.csv" with these estimates. 

**phenesse_analysis.Rmd:** This script performs the statistical analysis for the onset phenology estimates, and generates the data frame titled "ztest_df.csv"

**phenology_plots.Rmd:** This script uses the phenesse_estimates_df.csv data frame to generate all plots presented in the manuscript. 

**PACKAGE VERSION INFORMATION:** 
> packageVersion("curl")
[1] ‘5.2.1’
> packageVersion("sf")
[1] ‘1.0.16’
> packageVersion("ggplot2")
[1] ‘3.5.1’
> packageVersion("lubridate")
[1] ‘1.9.3’
> packageVersion("spData")
[1] ‘2.3.1’
> packageVersion("ggmap")
[1] ‘4.0.0’
> packageVersion("sp")
[1] ‘2.1.4’
> packageVersion("adehabitatHR")
[1] ‘0.4.21’
> packageVersion("maps")
[1] ‘3.4.2’
> packageVersion("ggpubr")
[1] ‘0.6.0’
> packageVersion("tidyverse")
[1] ‘2.0.0’
> packageVersion("dplyr")
[1] ‘1.1.4’
> packageVersion("phenesse")
[1] ‘0.1.2’
> packageVersion("gginnards")
[1] ‘0.2.0.1’
> packageVersion("tibble")
[1] ‘3.2.1’
> packageVersion("magrittr")
[1] ‘2.0.3’
> packageVersion("stringr")
[1] ‘1.5.1’


