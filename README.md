# Deprivation-and-mental-health-in-Liverpool
A project examining the impact that deprivation has on mental health need in Liverpool.

### Background
This project examines the relationship between deprivation (represented through the Index of Multiple Deprivation, IMD) and mental health need (represented through the Small Area Mental Health Index, SAMHI) through examining how mental health need changes based on deprivation. As a local authority, Liverpool has one of the highest proportions of most deprived neighbourhoods in England (see https://assets.publishing.service.gov.uk/media/5d8b387740f0b609909b5908/IoD2019_Technical_Report.pdf). Furthermore, Merseyside has a higher rate of depression (17.99%) than the national average (13.25%) (see https://commonslibrary.parliament.uk/constituency-data-how-healthy-is-your-area/). Therefore, it is beneficial to explore the factors influencing the relative poor mental health in the region.

### Code
The ```.ipynb``` creates a dataframe containing both the IMD and SAMHI scores for each LSOA in Liverpool. It then creates a regression to model the effect that IMD has on SAMHI. It goes on to map two choropleth maps spatially comparing the rate of deprivation with the level of mental health need in the area. Finally, it plots the regression line as well as two other graphs to aid interpretation of the model. Explanation and interpretation of the code and visualisations is provided throughout in markdown, with a conclusion at the end and references.

### Repo Contents
* assignment_201801028: the jupyter source file containing the code
* File_5_-_IoD2019_Scores: a Microsodt Excel ```.csv``` (comma separated values) file containing all the indices of deprivation for every LSOA in the country (note we are only concerned with one of these indices)
* liverpool lsoas: another ```.csv``` file with links to all the Liverpool LSOAs
* LSOA_2021_EW_BGC.zip: contains the LSOA_2021_EW_BGC.shp shapefile as this was too big to upload directly. The shapefile contains coordinates for the polygons representing each LSOA and thus gives us our spatial information.
* LSOA_2021_EW_BGC.cpg, LSOA_2021_EW_BGC.dbf, LSOA_2021_EW_BGC.prj, LSOA_2021_EW_BGC.shx: the files required by the shapefile.
* samhi_21_01_v4.00_2011_2019_LSOA: anothe ```.csv``` which contains the SAMHI deciles and scores from 2011 to 2019 by LSOA.

**N.B.:** You will need to unzip "LSOA_2021_EW_BGC.zip" to get the necessary shapefile.
