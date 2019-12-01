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
  
# Plan for Work

Analysis: The next big step is to start using combined tables to statistically     test the relationships which will answer the posed questions.
  These include the trends for discharge in the Skagit river over time. More       importantly, I need to complete the regression model for the relationship        between discharge and smolt outmigration.
  I also need to work on including trend lines for the plots that display these    analyses.
  
Joins: Before the analyses can be completed, I need to finish created the joined   tables that have all the required data for each individual analysis. 

Slides: I need to add some additional background information and images to the     introdcution slides to more accurately portray the importance of the question.
  The introduction should also include a slide explaining the nature of the        statistical analysis.
