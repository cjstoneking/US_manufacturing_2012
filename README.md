# US_census_2012

In this project, I take a large dataset from the 2012 US Census and use it to get a better understanding of how different manufacturing areas are reprented in different US states. This involves several steps of preprocessing in Python, followed by visualization in Tableau.  

The dataset consists of numbers of manufacturing businesses (called "Establishments" in census terminology),  
which are broken down by:  

a) the US state they are in\
b) the sector they are in\
c) the approximate number of employees they have

The original datafile is available from https://www.census.gov/data/datasets/2012/econ/census/2012-manufacturing.html, link under "State". The download has multiple files, the main datafile is ECN_2012_US_31SA1_with_ann.csv

I also use the 2012 census estimates of the state populations, which can be found under https://www.governing.com/gov-data/state-census-population-migration-births-deaths-estimates.html, or in the .csv which I added to this project.

I run some preprocessing on the ECN_2012_US_31SA1_with_ann.csv file to get numbers of businesses and estimated numbers of employees in different sectors for each state, then normalize by the estimates of the state population. The code for this is in the .ipynb notebook. The resulting file is US_Census_2012_manufacturing_per_10000_residents.csv.  

After preprocessing, I visualized some aspects of the data using Tableau. The visualization can be found at:  


https://public.tableau.com/profile/cjstoneking#!/vizhome/US_manufacturing_2012/Dashboard1



