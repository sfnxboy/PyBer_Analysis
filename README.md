# PyBer_Analysis

## Overview of the Analysis
This Read-Me refers to the Pyber_Challenge.ipynb file.
We had two main objectives, to create a data frame summarizing ride-sharing data by data type, and to create a multi-line chart of the total fares of each city type across several months. I used the pandas library for most of the technical analysis, as that allows a programmer the ability to draw data frames from csv files as well as manipulate the data within the data frame to express a meaningful story. After loading the two necessary .csv files, I merged them into a data frame. To make a summary of the data, I first used the .groupby() method to isolate relevant data, calculated informative averages using that date, and created a new summary data frame. The columns of the summary data frame were written using dictionary-esque format, including index names and values, where each column represented each collection of isolated data collected earlier. 

I used the MatPlotLib library to create the line chart, not just because an excel chart isn’t impressive enough, but more importantly because I could draw data from within the data frames created through pandas. MatPlotLib is a graphing and plotting library for Python that comes with the Anaconda software, as long as you import it in Jupyter Notebook (or other interface you wish to use), it can be readily utilized. The line chart made in the .ipynb file uses the object-oriented interface method.

## Analysis & Results


![image](https://user-images.githubusercontent.com/68082808/90998077-36c32a00-e591-11ea-9bc6-04af35068801.png)


### Total Rides
Urban cities have the greatest number of rides, with 1625.

Suburban cities have the second greatest number of rides, with 625.

Rural cities have the least number of rides, with 125.


### Total Drivers
Urban cities have the greatest number of drivers, with 2405.

Suburban cities have the second greatest number of drivers, with 490.

Rural cities have the least number of drivers, with 78.


### Total Fares
Urban cities have the greatest total fare, with $39,854.38.

Suburban cities have the second greatest total fare, with $19,356.33.

Rural cities have the least total fare, with $4,327.93.


### Average Fare per Ride
Urban cities have the least average fare per ride, with $24.53 per ride.

Suburban cities have the second greatest average fare per ride, with $30.96 per ride.

Rural Cities have the greatest average fare per ride, with $34.62 per ride.


### Average Fare per Driver
Urban cities have the least average fare per driver, with $16.57 per driver.

Suburban cities have the second greatest average fare per driver, with $39.50 per driver.

Rural Cities have the greatest average fare per driver, with $55.49 per driver.


## Business Recommendations and Notes
One can readily notice from the chart above that there are significantly more rides in urban locations, that they have more drivers, and that the total fare is greatest within the first four months of 2019. However, there is a more telling statistic, the average fare per ride in urban areas is less than that in suburban and rural areas. The average fare per driver is also less in those areas too. That may be for a variety of reasons. Firstly, perhaps the distance per ride within urban areas are shorter than those rides in suburban and rural areas, and therefore the average fare per ride and average fare per driver is lower in those areas. 

One thing the data does not indicate is the average number of rides per driver in each city-type. Perhaps one can find a good balance between drivers, and average fare per driver, and moderate a fair balance between number of drivers within each city type. A ride-share business can benefit a lot for making sure every city-type has a balanced number of drivers because then workers in more rural city-types are less likely to be overworked, and drivers in more urban city-types wouldn’t be paid for idling.

On the note of number of total drivers, there is a significantly larger number of drivers within urban cities than there are rides in rural cities, indicating that there are some drivers who did not get any rides. Perhaps this business would benefit from laying off a number of drivers in urban cities.
