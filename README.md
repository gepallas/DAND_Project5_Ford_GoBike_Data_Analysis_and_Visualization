# Ford GoBike Trips Data Analysis and Visualization
This project has been completed as part of the [Udacity's Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) requirements.

## Overview
In this project the electric bike trip data from Ford GoBike in the San Francisco Bay Area were gathered, assessed, cleaned, analyzed and visualized.

*The dataset includes more than 2,000,000 records of the Ford GoBike trips in the San Francisco Bay Area, for the years 2017 (from June) and 2018.*

The main characteristics for the behaviour of the different Ford GoBike user types are explored. There are two different types of users: Subscribers and Customers. 

Main characteristics explored (among others):
- When subscribers and customers use their bikes
- How long they use the bikes
- From which locations

Types of variable exploration:
- Univariate
- Bivariate
- Mutlivariate

## Technologies used
- Python
- Libaries: Pandas, NumPy, Zipfile, MatPlotlib, Seaborn
- Jupyter Notebook

## Snapshot from the Exploratory Data Analysis

The following Figure shows the number of trips per hour of the day by user type.

<p align="center">
  <img src="https://github.com/gepallas/DAND_Project5_Ford_GoBike_Data_Analysis_and_Visualization/blob/master/images/image1.png?raw=true" />
</p>

Subscribers are mostly using the bikes during the rush hours, while Customers are mostly using the bikes in the evenings and mostly equally during the rest of day. Subscribers are likely regular commuters while Customers are likely visitors at the city.

The next Figure shows daily number of trips by hour of the day by user type.

<p align="center">
  <img src="https://github.com/gepallas/DAND_Project5_Ford_GoBike_Data_Analysis_and_Visualization/blob/master/images/image2.png?raw=true" />
</p>

It is clearly shown in this slide that Subscribers are mostly travelling during the week and rush hours, from 8:00 to 9:00 and from 17:00 to 18:00, most likely commuting to/from work. Customers are mostly travelling on Saturdays, followed by the other days of the week, with an increasing trend from the morning, about 8:00, to the evening hours, about 18:00.
*Also notice: the scale of the number of trips from subscribers is one order of magnitude higher compared customers*

In the following graph the busiest stations by number of trips by user type is presented.

<p align="center">
  <img src="https://github.com/gepallas/DAND_Project5_Ford_GoBike_Data_Analysis_and_Visualization/blob/master/images/image3.png?raw=true" />
</p>

The busiest stations differ between the two bike user types. For Subscribers, for the top 10 busiest stations by number of trips, there is a more "linear" decrease in the "business" of the stations. For Customers however, there are two dominant stations by number of trips, and the rest are following!

These two stations are likely popular destinations/starting points for visitors/tourists. For example, we see that one of them is "San Francisco Ferry Building" which is a popular location for the visitors of the city.
