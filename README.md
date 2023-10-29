# PandemicFlightAnalysis

Overview
The goal of the project is to identify the most impactful flight routes during the pandemic to suggest aviation authorities
to minimize the flights in such a way as to control the spread of Covid-19 yet keep making sufficient profit.
Our proposed solution is to decrease the number of flights to a minimum per state utilising only those airports 
with most recurring and frequent flights so that travelers can reach their desired destinations, while lowering the spread of Covid-19.  

So we ask ourselves the question, is it possible to predict the most important flight routes during a pandemic?
By analyzing the most important airports and flights, we try to create a model that can classify an airport base on their 
flights to minimize the pandemic spread and maximize the profits of airlines while limiting the number of flights across the United States.  


## Data 

We have collected the data from Bureau of transportation mainly for years 2020, 2021




Checked for missing values and removed the rows where there is a NA value. (around 2%)
Identified the top 3 airports in each state based on number of flights that travel from that airport in the year. 
airport_label with value of 1 indicating the popularity of the airport.
From these most popular airports, we identified the flights to top 3 destinations.
flight_label with a value of 1 indicating the popularity of the flight.

Lacking in the price of each flights
Substitute by using the frequency of the flight.
Can not identify the connection flights
This can cause the results to have some error since some long distance flights have different connection flights

In 2020, there are 142 airports and there are 224 distinct flights from these airports considered as important.
In 2021, there are 143 airports and there are 214 distinct flights from these airports considered as important.
