# OaklandTickets
Data pipeline analysis and presentation of findings related to Parking tickets issued by the city of oakland as they relate to demographic and income data supplied by the American communities Survey

Objective:
To analyze parking ticket data from the city of Oakland, California in conjunction with data from the America Communities Survey in search of demographic and income markers that may indicate or predict the prevalence of parking tickets allocated to specific census bureau tracts. Following the identification of such markers, a predictive model will be developed and tested on different subsets throughout the many years of data provided.

Methodological overview:
Data Collection:
Source of parking ticket data -- https://data.oaklandca.gov/
    Data for the years from 2015 through 2019 were collected and aggregated one large file with the following information provided per ticket:
        --
Mapping Oakland addresses to Census tract --https://geocoding.geo.census.gov/geocoder/
    To make use of the data provided, each ticket's address was formatted to the census bureau's guidelines (https://www.census.gov/programs-surveys/geography/technical-documentation/complete-technical-documentation/census-geocoder.html) geocoded to match a specific census bureau tract so that it could be cross referenced to Data provided by the American communities demographic data.
Source of demographic data -- https://data.census.gov/cedsci/
    data relating to the makeup of the race, income, and population density was collected and organized by census bureau tract

Data cleaning and formatting: Python and Pandas
Data Analysis: MatPlotLib
Predictive modeling: SciKitlearn
