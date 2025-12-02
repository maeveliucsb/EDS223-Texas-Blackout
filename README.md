# EDS223-Texas-Blackout-Analysis
Analyzing the 2021 Texas blackouts


In this repository, I am analyzing the impacts of the 2021 blackouts in Texas, in which widespread power outages swept the state due to snow storms. This repository uses analytical skills including maneuvering large spatial datasets, using data from multiple sources, map algebra, and analyzing the socioeconomic impacts of extreme weather events. 


I am using the NASA VIIRS data to analyze the breadth of the blackouts by analyzing night light intensity changes before and after the blackouts. This data is combined with road data and home from open street map to ensure accuracy and minimize intervening variables like standard road light variability patterns, as well as to identify which homes lost power due to the extreme weather event. Finally, to analyze the socioeconomic effects of the blackouts, I use US Census data about median household income to observe area-level impacts stratified by socioeconomic status. 


# Data access:
No data is housed in ths repository, but I have given instructions for access for each dataset. 

NASA VIIRS

This data has been downloaded from Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC) from NASA, and I am using the dates with less cloud cover (2021-02-07 and 2021-02-16) and the spatial tiles of Houston (h08v05 and h08v06).

OpenStreetMap roads and houses

This data was downloaded using Geofabrik, which extracts data from OpenStreetMap. It contains data from the Houston Metropolitan area.

ACS

This is 2019 Census data from the U.S. Census Bureau’s American Community Survey, which is publically accessible

Authors and contributors

I am the sole author to this homework assignment. The assignment was written by Ruth Oliver and Annie Adams.


# Data citations:

NASA VIIRS

NASA VIIRS (Visible Infrared Imaging Radiometer Suite) Data 2021. Distributed through NASA Level-1 and Atmospheric Archive & Distribution System Distributed Active Archive Center (LAADS DAAC). https://ladsweb.modaps.eosdis.nasa.gov/

OpenStreetMap

This OpenStreetMap data used in this project is made available under the Open Database License: http://opendatacommons.org/licenses/odbl/1.0/. Any rights in individual contents of the database are licensed under the Database Contents License: http://opendatacommons.org/licenses/dbcl/1.0/

ACS
U.S. Census Bureau, 2019 Census. Accessed via https://www.census.gov/programs-surveys/acs.
