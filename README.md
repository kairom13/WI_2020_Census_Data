# WI_2020_Census_Data
Census data from the Census Bureau can be hard to get in clean formats. This repository separates the combined data from the Census Bureau's release of redistricting data for easier consumption and use. Extraneous columns have been removed and each file focuses on one geographic level of reporting of populations.

## Organization
- Each legislative district folder contains 6 files: 1 with the populations of each district and 5 that separate the populations by other geographies: American Indian reservations, Counties, Municipalities, School Districts, and Census Tracts.
- The statewide folder lists the populations by geography: American Indian reservations, Census Block Group, County, Municipality, School District, and Census Tract
- The voting district folder lists the populations of each voting district (VTD) as well as by other geographies: American Indian reservations, Counties, Municipalities, School Districts, Legislative Districts, and Census Tracts.
- WI_census_blocks.csv contains the populations of each Census Block as well which geography that block is in
- WI_census_data_dict.csv is the dictionary for each field name in orginial file. 
- WI_census_districts.csv contains the populations for each legislative district as well as the population deviation from average

## Source
The original data set, as well as other data files and data for other states, can be found here: https://www2.census.gov/programs-surveys/decennial/2020/data/01-Redistricting_File--PL_94-171/Wisconsin/
