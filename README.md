# Josef-discharge

# Required Packages

tidyverse
  -GGPlot
  -Dplyr
  -Knitr

# Documents in Order of Use

images/skagit_river_canyon.jpg
  Picture of fish barrier canyon before dams on skagit river
  
clean_data/avg_monthly_discharge.txt
  Average monthly discharge for every month of each year from 1941-2018. Data      gathered at USGS Mt Vernon site on the Skagit river. Discharge in cfs.
  
data/avg_daily_discharge.csv
  Average discharge for every day of the year. Means calculated with data from     1941-2018.Data gathered at USGS Mt Vernon site on the Skagit river. Discharge    in cfs.
  
data/steelhead_smolt_trapped.csv
  Counts of steelhead smolt trapped in either scoop (1990-2007) or screw           (1993-2007) traps on the Skagit river near Mt Vernon, Wa. 
  
# Scripts

01_data_import.Rmd
  Imports data, cleans it up for use in code, and describes the content as well    as any changes.
  
02_initial_plots.Rmd
  Provides plots of raw data for visualization and base analysis. 