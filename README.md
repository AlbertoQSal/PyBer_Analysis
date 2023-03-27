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
To create the multiple-line chart the data was grouped by type and date, and all the fares were sum to quantify the total of fares by day. Once the data was rearrenged, a pivot table was created to use the dates as rows, the type of city as columns and the fares as values, this DataFrame is shown in Figure 2.

<img width="293" alt="Captura de pantalla 2023-03-27 a la(s) 10 12 30" src="https://user-images.githubusercontent.com/93279134/228000483-5711ad92-d861-4bf9-9e09-6e4b3e4c79c4.png">

Figure 2. Fares by date DataFrame

Finally, to create the multiple-line chart, the previous DataFrame was filtered to only obtain data from january to april. Then, data was resample to obtain the sum the fares by week, the final DataFrame is shown in Figure 3.


<img width="278" alt="Captura de pantalla 2023-03-27 a la(s) 10 16 39" src="https://user-images.githubusercontent.com/93279134/228001461-56b808ce-33e9-4104-a22a-5c2c8ec3b4fa.png">

Figure 3. Fares by week DataFrame.

Based on the DataFrame shown in Figure 3, the multiple-line chart was created.

![image](https://user-images.githubusercontent.com/93279134/228001850-a85e8172-21bc-4204-8449-e63324cdfe4e.png)

Figure 4. Multiple-line Chart.

## Summary 
Based on the chart and in the information shown in the Figure 1, we can see that the type of city that has the greater amount of rides is the urban type, but they have the smallest average fare. In order to overcome this disparity between city types, I suggest three main strategies:

- Creating offers and stimulus in the rural cities, this can overcome the elevated fare and can help drive the usage of the service.
- Using dynamic fares in urban cities, this may help out the drivers to get a bit more of money out of each ride, in Figure 1 we can see that there are more drivers than rides in the urban city, so if we create a dynamic fare for them, they may improve their service and their profits.
- Performing a market study in each city, this studies will help us out to create a proper marketing campaign  for each city where we, as a brand, could adapt to the needs of each place. It's important to understand our customer for us to improve.

