# Python----bike_share_exploration
San Francisco Bay Area Bike-Sharing System Exploration

## Dataset

The data consisted of trip and user details for each bike using at Feb 2019 approximately 175000 trip. The attributes included the start and end (time and station) details, as well as user (gender, birth year, subscription) details.

We removed trips with missing data (8462) trip
Since the main idea of bike share is using bike to move inside city fast from point to point not keeping bike with customer for long time or next day, so we slecte the max period of bike usage is 45 minutes and remove dataset whcih exceed that limit (2306) trip
Also we removed we remove all trips for subscribers above 80 old as we suspect that it's false data as bike is not safe for aging people (203) trip

## Summary of Findings

The duration in seconds took on a large range of values, so I looked at the data using a log transform, 
under the transformation, the data looked unimodal, with one peak between 5 and 15 minutes

Also it's clear the people depend on biks share system as transportation methoud to go to work and return back 
after working hours as in weekdays at 8 AM and 5 PM represnt the maximum trips counts

The relation between age members and duration of using bikes represent that most people using the bike share system is 
between 20 and 40 years old and mostly using bike for less than 10 minutes trip.

Number of trips at weekdays is about douple than weekends but on average at weekends duration spent on 
using bikes is slightly more than weekdays

While Males are doing more trips than Females on bike share system with Large Difference 
but on average Females are spending more time in using bikes with Littel Difference

Also we found 9 stations already exist in both most 10 Start and End stations

We noticed after midnight the difference increased as females prefer using bike rather than walking maybe for saftey issues

## Key Insights for Presentation

We foucsed on the dirtribution of duration as main factor using starting time of trip to get the average time of using bike
then check the number of trips per hour over the day to get the most crowded hours on requesting the servise, 
then we checked the difference in using bikes between weekday and weekeds. 

After that we check the relations between user age and numbers of trips made and its duration

Finaly we make compare between males and females for number of trips and its duration
