# PyBer_Analysis

## Overview of the Analysis
- The CEO of PyBer, V. Isualize, has tasked me and Omar to show how the data looks like depending on the total rides, total drivers and total fare by city type. We also have been tasked to show the total weekly fares by each type of city for the first trimester of the year. To do this we will need to use pandas library to create the DataFrames we need and matplotlib to be able to show the visualization on those DataFrames.

## Results
### PyBer Ride-Sharing Data (2019)
- On the graph below we can get a general idea of all the data we have been given, and since the bubbles size depend on the number of drivers per city type we can easily verify that there are less drivers in the rural and suburban areas compared to urban areas. We can also see that both suburban and rural drivers have a bigger Fare($USD) in average but they also have less rides.
!['PyBer Ride-Sharing Data (2019)'](/analysis/Fig1.png)
### Fares by City Type
- Below we verify 62.7% of the total fare is urban alone, with a 30.5% going to suburban areas and 6.8% to rural areas. We also see rural areas beat the average of the fares for urban areas by about $12 and $7 if compared to suburban areas.
!['Fares by City Type'](/analysis/Fig3.png)
!['Fares by City Type'](/analysis/Fig5.png)
### Rides by City Type
- On this next graph we see 68.4% of the rides were in urban areas, 26.3% were in suburban areas and 5.3% were in rural areas.
!['Rides by City Type'](/analysis/Fig6.png)

### Drivers by City Type
- On this graph we can see pac-man(Urban drivers) eating the ghosts(Suburban & Rural drivers) with an 80.9% of the drivers being in urban areas, 16.5% and 2.6% being suburban and rural drivers respectively.
!['Drivers by City Type'](/analysis/Fig7.png)

### First trimester 2019
- With this graph we can see the total of the fares by city types and how they improved or worsen each week of the first trimester of 2019.
!['trimester'](/analysis/PyBer_fare_summary.png)

## Summary
- We can see some disparities among the city types, specially in urban areas compared to others. To improve this there are a few things we can do:
    1. Rural city type average fares are higher than any other types of cities, this could be due to the rural city type being more spreadout when going from one place to the other compared to the other types, making the fare on its own higher. To test the legitimacy of our theory we should include the distance data in the data collection and analysis process.
    2. As shown on "Drivers by City Type" and "Rides by City Type" we can see 80.9% of the drivers are in urban areas but total rides on urban areas making up only 68.4%. This tells us there are more drivers in urban areas than there are rides. Showing urban city drivers the average rural city drivers make compared to theirs should help filling the need between drivers and rides in both urban and rural areas. This will help urban drivers make more money and will help the customers in rural areas with more drivers and less wait time.
    3. Even tho urban cities get the most revenue and the most drivers increasing the prices would only drive customers away from using PyBer in urban cities. What could be done is 1 - as mentioned above, advertise the average fares by city type to urban drivers, 2 - PyBer could use promotions and discounts on urban riders to increase the number of rides in urban areas. More riders equals more drivers working bringing the disparaty from rides and drivers down, and subsequently more revenue in total for the drivers as well as for PyBer.
