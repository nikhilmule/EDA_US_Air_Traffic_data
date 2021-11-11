# EDA_US_Air_Traffic_data
![image](https://user-images.githubusercontent.com/77428032/141299590-20ea68da-258c-4b24-b32b-4e45922d9f21.png)

## Objective

- ### __The main objective of this analysis is to find the distance between two loactions (starting and ending)__
- ### __Find the max distance by carrier 0, carrier 1, maximum starting location__

## Explanation

- ### __In this analysis geopy, pydeck, geopandas, pandas, matplot, shapely libraries are used.__

# __Conculsion__

### Based on the descriptive analysis on the original dataset. It found that MIA - Miami International Airport is mostly used US Airport

    - Intitally in this analysis. Carrier group 1 were analyzed first which are "US" domestic air carriers
    - Next Carrier group 0 were analyzed first which are "foreign" domestic air carriers

### Random sample is taken from this dataset for carrier group "1" and "0" with size of 500 and size is considered based on the confidence interval, confidence level

### In this analysis distance between two locations is calcaulated by using geopy library

### Intitally visulaization is done by using the "geopandas" but in order to make attractive visualiaztion "pydeck" library utilized.

### __Final__

    - For carrier group '1'. In year 2001 peak year
    - For carrier group '0'. In year 2013 is peak year
    - In year 2007 is airlines from MIA (MIA - Miami International Airport) travelled longer distances (based on the mean)
Note: Please run the file to see visualiaztion output of 'pydeck' library
