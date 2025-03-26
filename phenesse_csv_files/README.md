# Code for: Citizen science supports ecological predictions of phenology in a butterfly mimicry complex

**DATA CITATION:** iNaturalist contributors, iNaturalist (2025). iNaturalist Research-grade Observations. iNaturalist.org. Occurrence dataset https://doi.org/10.15468/ab3s5x accessed via GBIF.org on 2025-03-19.

**phenesse_csv_files:** This folder contains all csv files generated from scripts in the phenesse_scripts folder.

butterfly_adults_capped.csv: This csv file contains all observations of adult butterflies from iNaturalist research-grade records  for Battus philenor, Limenitis arthemis astyanax, Danaus plexippus, and Limenitis archippus. Observations have been capped to include only 1 observation per species per day within a 7km radius

GBIF_phenesse_estimates_df.csv: This csv file contains all phenology estimates (in Julian days) for Battus philenor, Limenitis arthemis astyanax, Danaus plexippus, and Limenitis archippus. Phenology estimates were generated using the phenesse package. Samples sizes indicate total records for each species within each latitudinal bin. Low and high 95% confidence intervals are also provided.

onset_estimates_dates.csv: This csv file contains the onset estimates included in the "GBIF_phenesse_estimates_df.csv" file, but also provides the onset dates in yyyy-mm-dd format.

ztest_df.csv: This csv file contains the results of two-sample z-tests comparing onset phenology estimates between Battus philenor and Limenitis arthemis astyanax, and Danaus plexippus and Limenitis archippus. The z-test results include the z-statistic and p-value. 

ztest_bat_ast.csv: This csv file contains the results of two-sample z-tests comparing onset phenology estimates between Battus philenor (bat) and Limenitis arthemis astyanax (ast). The z-test results include the z-statistic and p-value, and the estimated delay in emergence. 

ztest_plex_arc.csv: This csv file contains the results of two-sample z-tests comparing onset phenology estimates between Danaus plexippus (plex) and Limenitis archippus (arc). The z-test results include the z-statistic and p-value, and the estimated delay in emergence.
