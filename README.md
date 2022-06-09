# _PyBer_Analysis_

## Overview of the analysis:

This analysis summarises the ride-sharing data categorised by city and type and to visualise this information for better understanding of the available data. For the purpose of the analysis we use the merged data from two csv files - city_data.csv & ride_data.csv and create dataframes based on city types - Rural, Suburban and Urban.


## Results:

The analysed data is summarized on the basis of city type - Rural, Suburban & Urban. Against each of these city types the values for total rides, total drivers, total fares, average fare per ride and average fare per driver are listed in a dataframe.

A screenshot of this dataframe is enclosed below.

![Summary_DF](https://user-images.githubusercontent.com/104603128/172955181-099f44d2-95a3-4e15-af5b-59a5425b4985.JPG)

In this screenshot it can be seen that total rides are *highest* for urban cities and *lowest* for rural cities with suburban cities in between. Similar figures are seen for the total drivers & total fares. However, this trend changes when we see the average fare per ride and per driver for different city types. For rural cities the average fare per ride and average fare per driver is the *highest* followed by suburban cities and *least* for urban cities.


![PyBer_fare_summary](https://user-images.githubusercontent.com/104603128/172954967-afe61593-dfcb-40ea-be71-c66fe42183eb.png)

## Summary:

* Rural areas have the least driver count despite having the highest average fares. To increase revenues from these cities it might be beneficial to _add more drivers_. Similar approach can be used on suburban areas as well.

* Rural areas have the least ride counts. To increase revenues it might be beneficial to _focus on increasing these figures_.

* Urban areas have the least average fares despite having the highest driver count. To increase revenues from these cities it might be beneficial to _increase the average fares_. 
