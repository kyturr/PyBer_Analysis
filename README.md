# PyBer_Analysis

## Overview of the Analysis
The ride-share company PyBer has requested analysis on ride data that culminates in easy to follow charts and graphs that compare various aspects of the ride-sharing data specifically amongst the different city types. The analysis will compare Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver, as well as the weekly total fares from the months of January through late April of 2019. These results are to be obtained using the python method matplotlib to make the visual aids.

## Results

The following table was created by grouping the data by type of city and performing functions such as sum and count.

![image](https://user-images.githubusercontent.com/103979048/176546824-e02088f5-0c56-4a38-9a7a-088fea704206.png)

Based on these results, we can see that urban rides represent a vast majority of each of the company’s totals.  However, when taking into account the Average Fare per Ride and Average Fare per Driver, it is clear that the more lucrative city type to be driving in is the Rural area. These drivers make over three times the fares per driver and make $10 more per ride on average. There are more total rides in Urban but a disproportionately larger number of drivers, which means more competition and less money per driver. Add in that the average fare per ride is greatly reduced and the large difference in fare per driver makes much more sense. For rural and suburban spaces there were less drivers than total rides meaning some drivers were accounting for multiple rides. For urban space there are more total drivers than rides so at least almost 800 of the drivers in urban space did not register a single ride. If some drivers were able to give multiple rides then that number of rideless drivers could be even higher.

We can look at the money each city type makes on a week to week basis in the following multiple-line chart.

![image](https://user-images.githubusercontent.com/103979048/176546901-586e2cda-e396-422d-8c94-723ae1655a32.png)

From this chart it is clear to see that the Urban space consistently has the most fares. It does not seem there is any particular relationship between the fares i.e. fares rise together or one falls and one rises. There does seem to be a universal increase in fares in the last week of February which might be worth investigating what might have driven so many rides that week. 


## Summary

There are a few recommendations I can make to the CEO to address the disparities among the city types.

First, it would be helpful to encourage drivers to base out of rural or suburban areas instead of urban areas. One of the causes of the disparity is that there is a high concentration of drivers in the urban space making up 86 % of all drivers. If more of those drivers were in rural and suburban areas, the fare per driver would be more equal. Specifically, looking at the chart below, taking drivers from cities with large bubbles that are left most (low numbers of rides per city) and moving them to base out of cities that are small bubbles that are right most will help reduce the average fare per driver in those areas.

![Fig1](https://user-images.githubusercontent.com/103979048/176547007-e8bbf869-c1f8-46c3-987c-8b1c64115444.png)

Next, it might be helpful to impose limits to the amount of drivers in a given city based on the total number of rides per city. That way, the supply more closely matches the demand. Reducing the amount of drivers in urban areas will allow the remaining drivers to give rides more consistently and will help increase the fares per driver for those areas.

Finally, the CEO could invest in greater marketing in urban areas. Increasing the amount of rides will be worth the money invested and will decrease the disparity between the amount of rides and the amount of drivers in urban areas. Conversely, investing in greater marketing in all areas can decrease the disparity in percent of fares of each city type, and so long as drivers are shifted around to meet the demand, it should also result in an evening of the rates per driver of each location.

There are a couple more statistics and graphs that might be helpful in the future. For data collected, it might be helpful to also collect the distance traveled for each ride. With this data, average distance per ride can be calculated. This might help to explain the larger fares in Rural spaces as they might be traveling further which also would mean likely having to return from the drop off point without driving anyone back as well as having to drive a long distance to pick another person up, whereas in an Urban space there is likely to be another customer needing a ride near the drop off point. Different statistics might help paint a better picture of what is going on in the streets and may lead to additional insights that will lead to a more optimized company.
