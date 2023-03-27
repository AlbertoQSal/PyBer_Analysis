# PyBer_Analysis
## Overview
For this challenge I used Pyhton to create a ride-sharing summary dataframe. Then, using pandas and matplotlib a multiple-line chart was created to show the differences in the total weekly fares for each city type. The main objective of this analysis is to understand the differences in the behaviour of the ride-sharing service among the types of cities.

## Results
### Summary DataFrame
The summary DataFrame consisted in five columns which help to identify the differences between each type of city. 
- Total Rides: Using the groupby() function and the count() method, the total number of rides for each type of city was quantified.
- Total Drivers: Using the groupby() function and the sum() method, the total number of drivers for each type of city was quantified.
- Total Fares: Using the groupby() function and the sum() method, the total amount of fares for each type of city was quantified.
- Average Fare per Ride: Dividing the Total Fares column by the Total Rides column, the average fare per type of ride was calculated.
- Average Fare per Driver: Dividing the Total Fares column by the Total drivers column, the average fare per type of ride was calculated.


Once each column was cretaed, they were joint in a common DataFrame. The resulting DataFrame it's shown in Figure 1.


![Captura de pantalla 2023-03-26 a la(s) 23 50 15](https://user-images.githubusercontent.com/93279134/227851934-9d119ef5-4157-4e98-9a06-80fe6515bab0.png)

Figure 1. Pyber Summary DataFrame

### Multiple-line Chart


## Summary 
