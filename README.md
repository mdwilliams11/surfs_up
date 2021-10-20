# surfs_up
Module 9 repo

## Overview of the analysis
In this module we utilized Python, Pandas, and SQLAlchemy to analyze data from a SQLite file containing weather data from Oahu, Hawaii.
In this challenge we're going to analyze the temperature data for the months of June and December in Oahu, 
in order to determine if a potential surf and ice cream shop business is sustainable year-round.



## Results

* The June temperatures fall within a range of 64 - 85 degrees. The December temperatures fall within a range of 56 - 83 degrees.

* The average June temperature of 74.94 is only 3.9 degrees higher than the December average tempurature of 71.04 degrees.

* The tempuratures in December tend to have more variance than June, as shown in the higher standard deviation. The biggest difference
between the two month's tempurates is their minimum. The lowest December tempurature is 8 degrees lower than the lowest June tempurature.


![Any_title](https://raw.githubusercontent.com/mdwilliams11/surfs_up/main/jun_dec_describe.png)



## Summary

In addition to the analysis already performed it would be beneficial to also look at the precipitation between various months of the year.
Looking at precipitation data between months can help determine if there might be any slower months where surfers would be less likely to surf due to poor weather.

Looking at each month might not be granular enough to get a sense of rain patterns.
An additional way of looking at precipitation is to create a query that counts the number of days per month that exceed a certain threshhold of rainfall.
This would give a better view of how many days it rains vs the average statistics we would get just looking at inidivdual months.



