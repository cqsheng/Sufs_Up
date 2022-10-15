# An Analysis of Oahu Weather

## Overview of Project
    This project is used to determine the temperature trends of Oahu for June and December.
### Purpose
    The purpose is to determine whether the temperature year round is good enough to sustain a surf and ice cream shop for Oahu. The data is retrieved from a SQLite datafile and the statistics for the months of June and December is analyzed to determine how well the temperature is year round.

## Results
    The different temperature results will be addressed here, and a picture of the summary statistics will accompany it where helpful. The results are located in the Resources folder.
### The Decemeber data doesn't exist yet for the year of 2017, leading to less data points then the June data with only 1517 for December compared to June's 1700.
    
![](/Resources/Dec.png)
![](/Resources/June.png)
### Looking at the pictures above, the minimum temperature for June is 64 degress which should be warm enough. With 75% of temperatures being 73 or above with a overall average of nearly 75 degress June seems more than warm enough which not being too hot with a max temperature of 85 degrees.

### Looking at the pictures above, the minimum temperature for Decemeber is only 56 degress which might be a bit too cold for that day. However with 75% of temperatures being 69 or above with a overall average of 71 degress December seems warm enough for the majority of days to be sustainable.
    
## Summary
    The analysis was effective at showing the shop should be sustainable year round by looking at the temperature history of Oahu for June and Decemeber. However there are more queries that could give a more accurate result.
### 1.Looking at the data for other months:
    Currently the data is only gathered for June and December, which we assumed to be the hottest and coldest months but that could be wrong. Expanding the query to look at the temperature data for other months could return hotter or colder temperatures which the shop might not be viable during that month.
### 2.See how much it rains in Oahu:
    The SQLite contains data on how much it rains, having too much rain could cause the shop to not be viable as people are less likely to go to the beach on rainly days. Looking at the data for this could show how many days has heavy enough rains to turn away customers and see if this number is too high to have a sustainable shop year round.
