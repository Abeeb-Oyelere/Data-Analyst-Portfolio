# Diamonds Data Exploration

## Dataset

The data set contains information about individual rides made in a bike-sharing system 
covering the greater San Francisco Bay area for approximately 183,400 trips within 
the month of February 2019. 8460 data points were removed from the analysis 
due to inconsistencies or missing information.
repository for data can be found [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv).


## Summary of Findings

In the exploration, I found that there was a strong relationship between the
volume and duration of rides and the start time and day. Higher volume of ride are taken between
8-9am and 5-6pm of each days, and on Tuesdays and Thursdays
The durarion of ride on the other hand are highest within 3am of each days and 
on weekends(Saturday and Sunday). Though the number of male riders are highest among the genders,
those that classify as neither male nor female takes the highest average duration of trip. Also, while 
the volume of rides taken by subscribers are much more thann that taken my customers, customers have the highest average duration of trips.


## Key Insights for Presentation

For the presentation, I focus on just the influence of trip start time as well as riders gender and riders member
status on the duration on ride taken. I start by introducing the frequency of the trip duration, Afterwards, I introduce each of the categorical variables one by one. To start, I use the hist and bar plots of start time, gender and member status. 
Then I later focus on how the start time, (time and day) affect duration. The other two categorical
variables, gender and member status, are covered afterwards, using bar plots. I've made
sure to use different color palettes for each variable to make sure it
is clear that they're different between plots.
