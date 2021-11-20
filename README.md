# Improving ride share services through data-based decision-making

## Overview
With the goal of providing data driven insights to improve people's access to ride-sharing services, two datasets containing information about urban, suburban and rural cities using ride share services in 2019 as well as data on each ride conducted in these cities were analyzed.

## Resources
Data Source: city_data.csv, ride_data.csv
Software: Python 3.8.9, Jupyter Notebook

## Results
Table 1 shows the summary statistics.
As seen in Table 1, there are more rides in urban cities (N = 1,625), compared to suburban (N = 625) and rural (N = 125) ones. Urban cities have also more drivers and a larger amount of total ride fares, relative to suburban and rural cities. As a consequence, the average fare per ride and per driver are lower for urban cities than suburban and rural ones.

Add Table: Summary DataFrame

Taking a closer look at the total fare per city type (see Figure 1), it is possible to identify that the fares have some fluctuation through time but that the distance between cities does not change much from January to April 2019. The total fare were consistently higher for urban cities, followed by Suburban and then Rural.

Add Figure: multiple-line chart

## Summary
In sum, there is a clear disparity among urban, suburban and rural cities with respect to number of rides, number of drivers and total fares collected. Urban cities tend to have more rides, more dirvers and gather more fares, than suburban and urban cities. There is also a clear disparity among city types with respect to the average fare per ride and per drivers. Fares per ride and per drivers in rural and suburban cities tend to be more expensive than fares in urban cities. 

Based on these results, it is possible to infer that rural and suburban areas access to ride-sharing services can be improved by increasing the number of drivers in these cities or lowering the average cost of rides in these city types. This inference, although plausible, grants further analysis as it is possible that the increased average fare is also caused by the longer ride distances.
