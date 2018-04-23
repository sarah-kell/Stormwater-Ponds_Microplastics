# Stormwater-Ponds_Microplastics
Repository for analysis of microplastics in stormwater ponds and tidal creeks

Project objective: assess the contribution of non-point stormwater detention ponds to tire wear particle/microplastic debris in adjacent receiving tidal waterbodies.

Data generation:  Total microplastic (MP) concentrations were randomly generated using the rnorm function in R and then manipulated in Excel to simulate expected results of decreasing microplastic concentrations as you move downstream from the discharge point.  Tidal creek (water and sediment) MP abundances were based on average concentrations found in the rivers (Ashley, Cooper and Wando) feeding into Charleston Harbor. Sediment data generated for stormwater ponds was based upon preliminary data (max concentrations) for bottom and edge sediment; water sample data was based upon river data (there was no prelim data available for water in ponds).
*All results/conclusions noted are from randomly generated data

Instructions for Use: 
R code can be found in the Script.Rmd file.  Data that was generated and manipulated for the project is located in the SWponds.csv file.  All graphs are located in the Figures.file.   

In R: install vegan, dummies, car, dplyr and PMCMR packages if needed and load in libraries.  The R markdown file walks you though each analysis step by step with results noted.   

Abbrevations/Descriptions
SWponds = stormwater ponds;
RW = Receiving waterbodies; 
RW Up 50 = Receiving waterbody sampled 50 meters upstream from discharge pt;
RW Down 50 = Receiving waterbody sampled 50 meters downstream from discharge pt;
RW Down 100 = Receiving waterbody sampled 100 meters upstream from discharge pt;
Dicharge Pt = point where outflow from stormwater pond meets the tidal waterbody


