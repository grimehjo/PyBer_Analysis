# PyBer_Analysis
## Overview of the analysis: Explain the purpose of the new analysis.

In this module, I created visualizations of rideshare data for a company named PyBer (Which I believe is a portmanteau of 'Python' and 'Uber'). This was done with the purpose of helping improve access to ride-sharing services and determine affordability for underserved neighborhoods. 

I was supplied ride share data from PyBer from January to May 2019, the data was comprehensive and consisted of fares, city, ride id, the amount of rides, driver count, and type of locale/area (differentiated between rural, suburban, and urban). Ride-sharing data included total rides, total drivers, total fares, average fare per ride and driver, and total fare by city type etc. 

I created visualizations for the CEO that compared average fare by type of locale, average amount of rides by type of locale, percent of total fares by type of locale, percent of total rides by type of locale, percent of total drivers by type of locale, etc. These visualizations show some important business trends for PyBer, and also may be helpful in creating PyBer's future business strategy.

For the module challenge analysis, I was asked by Pyber's CEO to create a summary DataFrame of the ride-sharing data by city type. I was then instructed to utilize Pandas and Matplotlib to create a multiple-line graph which showed the total weekly fares for each city type. 

## Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
![Fig1](https://user-images.githubusercontent.com/80979705/122522141-9fc5d380-cfe3-11eb-8957-0afb10905a7b.png)
![Fig2](https://user-images.githubusercontent.com/80979705/122522154-a2c0c400-cfe3-11eb-8812-ad9da59cc9ac.png)
![Fig5](https://user-images.githubusercontent.com/80979705/122522179-a7857800-cfe3-11eb-9876-4d37e3063c92.png)
![Fig6](https://user-images.githubusercontent.com/80979705/122522184-a9e7d200-cfe3-11eb-8bcb-c8050b04af47.png)
![Fig7](https://user-images.githubusercontent.com/80979705/122522192-abb19580-cfe3-11eb-8dc3-5d7b135769b1.png)

 ### Findings
 - If we compare the average number of rides between each city type, we'll notice that the average number of rides in the rural cities is about 4 and 3.5 times lower than urban and suburban cities, respectively.

 - There is one outlier in the urban ride count data. Also, the average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and suburban cities, respectively.

 - From the combined box-and-whisker plots, we see that there are no outliers. However, the average fare for rides in the rural cities is about $11 and $5 more per ride than the urban and suburban cities, respectively.

 - The average number of drivers in rural cities is nine to four times less per city than in urban and suburban cities, respectively. Its obvious from looking at the above data that most of PyBer's revenue is made in Urban and Suburban areas, with less total revenue being created in rural areas.

The dominance of the Urban market in PyBer's total revenue is easily seen when looking at the multi line graph made during the challenge (Deliverable 2, specifically)
Clearly Pyber makes most its money in urban areas, followed by suburban areas. PyBer makes the least amount of money in rural areas. These facts are made clear when looking at the graph below.

![PyBer_fare_summary](https://user-images.githubusercontent.com/80979705/122522199-aeac8600-cfe3-11eb-8241-62e30cfcae6d.png)

## Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

### 1.) Enhancing Suburban Growth

While PyBer still makes most of its money in urban areas, revenue coming in from suburban areas is growing at a faster rate than urban areas. urban area revenue is declining while suburban area revenue is growing. In the near future, PyBer may make most of its money in the Suburbs- so its important to focus on this growth with greater advertising and marketing, while also making sure the service stays accessible and reliable for new suburban consumers with many drivers, competive drivers, and short wait times.

### 2.) Long term Investments in Rural Areas

While rural areas are the weakest type of locale for PyBer at the moment, the rural areas also suffer from a severe lack of drivers. Fewer drivers often means longer wait times and less assesibility for the few rural customers PyBer does have, meaning worse customer experiences in a no good postitive feedback loop. While it may be costly at first, it may be smart for PyBer to hire more drivers in rural areas as an investment in the company's future there. If it becomes easier to use Pyber in rural areas, word might spread and more users may start using the service. With a larger user base, these areas could become more profitable in the future. While the low population density is a net negative for a ride share service like PyBer in rural locations, the lack of public transit and dependancy on cars in these areas may make up for this.

### 3.) Avoid Urban Stagnation

Urban areas are the breadwinner market for PyBer at the moment, but the visualization above shows that recent total fares in urban areas have been declining relative to all areas. This is not good. Policies must be made to ensure PyBer continues to grow and hold on to its user base in urban areas. Promotions, marketing, and greater advertising must be utilised as strategies to turn things around in urban areas.
