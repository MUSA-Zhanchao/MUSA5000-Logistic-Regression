# MUSA5000 Assignment 3: The Application of Logistic Regression to Examine the Predictors of Car Crashes Caused by Alcohol

**Authors: Zhanchao Yang, Haoyu Zhu, Kavana Raju**

## Assignment Overview
According to the US Department of Transportation, almost 30 people a day – or approximately one person every 51 minutes – die in motor vehicle crashes that involve an alcohol-impaired driver. Many more individuals are injured in these crashes.

A recent study conducted by the National Highway Traffic Safety Administration has shown that the economic impact of alcohol-related crashes is estimated to be more than $59 billion annually.

For more information, see [the website of the Centers for Disease Control and Prevention](https://www.cdc.gov/motorvehiclesafety/impaired_driving/impaired-drv_factsheet.html).
The goal of the current assignment is to identify predictors of accidents related to drunk driving. The data used in this assignment come from a data set containing all 53,260 car crashes in the City of Philadelphia for the years 2008 – 2012. The data set was compiled by the Pennsylvania Department of Transportation, and is made available to the public at OpenDataPhilly.org. In the past, Azavea, one of Philadelphia’s most prominent GIS software development firms, has used these data for a number of interesting analyses, which have been published on the company’s [website](https://element84.com/).

Because the crash data are geocoded, it is possible to spatially join the data to the 2000 Census block group level data set that was used for the two previous homework assignments. After the spatial join, each crash point contains the median household income and the percent of individuals with at least a bachelor’s degree in the block group where the crash took place.
