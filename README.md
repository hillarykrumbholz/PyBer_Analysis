# PyBer Analysis

### Project Overview
To create visualizations of rideshare data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods. In addition to scatter and pie charts, the CEO would like to see a summary table of key metrics of the ride-sharing data by city type, and a multiple-line graph that shows the average fare for each week by each city type.

### Resources
- Data Source: city_data.csv ride_data.csv
- Software: Python 3.6.9, Jupyter Notebook, Pandas Library, MatPLotLib

### Objectives
- Create a new PyBer Summary DataFrame
- Create a Multiple-Line Plot for the Sum of the Fares for Each City Type

### Summary of Data Explained in DataFrame

![Summary_DataFrame](https://github.com/hillarykrumbholz/PyBer_Analysis/blob/master/analysis/PyBer_Summary_DataFrame.png)

This table shows the key metrics of the ride-sharing company PyBer, and is categorized by city type. The table displays the Total Rides, Total Drivers, Total Fares, Average Fare per Ride and Average Fare per Driver for 3 city types – Rural, Suburban, and Urban. You can see that the number of rides and drivers are low in rural areas, but increase as you move into suburban areas, and are at the highest in urban areas. The number of total rides is 13 times greater in urban areas compared to rural; and the total number of drivers is nearly 31 times greater in urban areas compared to rural city types. The total amount of fares is also much greater in urban areas compared to suburban and rural areas, with bringing in 2 times and 9 times as much, respectively. When looking at the average fare per ride, you can see that rides cost about $10 less on average in urban areas compared to rural areas; and the average fare per driver is much greater in rural areas, with there being nearly a $39 difference when compared to urban areas. 

### Summary of Data Displayed in the Multiple-line Chart 

![Total_Fare_by_City_type](https://github.com/hillarykrumbholz/PyBer_Analysis/blob/master/analysis/PyBer_Total_Fare_by_City.png)

This line chart illustrates the average fares for each week between the months of January and April 2019, for each city type – Rural (blue), Suburban (red), and Urban (mustard). All city types display a similar trend that stays generally consistent through the months. All city types started on the lower end in January and saw a spike in average fares the end of February to mid-March. Rural areas consistently have the lowest fare total compared to suburban and urban types, with urban areas consistently having the greatest total fare. The weekly average fare for rural areas ranges from $0-500; suburban areas range from approximately $700-1500 per week; urban areas have a range from $1600-2500 per week. Urban areas bring in majority of revenue for PyBer with generating about twice as much revenue than suburban areas and nearly 5 times as much revenue than rural areas. 

### Explanation of the Implication of the Data Summary

The information presented on the summary dataframe table suggests there is a higher demand for PyBer rides in urban cities, possibly as a result of there being a denser population and increased traffic compared to rural and even suburban areas. Similarly, there is a greater number of drivers in urban areas to keep up with the demand of rides, which allows urban cities to bring in roughly 62% of revenue for PyBer. Consequently, because there are enough drivers to keep up with the demand, the average fare price is cheapest in urban cities. As you move out to the suburbs and rural areas, the fare per ride increases. This is most likely a result of there not being as many drivers available, but it could also be that each ride is longer and covering a greater distance in non-urban areas, thereby increasing the average fare per ride. However, when you look at the average fare per driver, it is much more lucrative to be a driver in rural and even suburban areas, compared to urban. Drivers in rural areas make nearly 3.5 times more money per ride, compared to drivers in urban cities. This is likely due to there not being enough drivers in rural areas, so there is less competition and prices can then get driven up. The information illustrated in the Total Fare by City Type multi-line graph also suggests that urban areas are generating the greatest amount of revenue for Pyber, which can be explained by the higher demand as a result of a denser population and increased traffic. Another factor could be that rides in rural areas are not affordable for the rider, so they opt not to use PyBer, thus bringing in the lowest amount of revenue.

With these two visualizations, I would suggest that there needs to be a continuous effort put forth in urban areas by making sure that there are enough drivers to keep up with the demand of rides. As PyBer gains popularity, more rides will be demanded, and the best way to keep prices steady is to keep up with the number of drivers available. As of now, rural areas are underserved and have the least affordable ride-sharing options. A way to bring prices down for those areas and to up the incentive of using PyBer would be to increase the number of drivers in those areas, which would bring the fare per ride down. You could also offer some sort of promotional deal for riders in rural areas. I suggest getting more data for rural and suburban city types to see the average distance per trip, this would allow you to get a better insight as to why the average fare per ride is $10 more than in other areas. 
