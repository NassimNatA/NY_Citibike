# NY Citibike Analysis 

## Link to Tableau Public Story 
[link to dashboard](https://public.tableau.com/profile/nassim7838#!/vizhome/Challenge14_Story/Story4?publish=yes)

## Overview of the analysis
The purpose of this project is to support the proposal of a bike-sharing investment to stakeholders based on in-depth analysis that will demonstrate the following: 
- Length of time that bikes are checked out for all riders and genders
- The number of bike trips for all riders and genders for each hour of each day of the week
- The number of bike trips for each type of user and gender for each day of the week.
From these characteristics of the business, it will be determined if trends are evident that support the investment of the bike-sharing program. In order to conduct this research, tableau will be used for data visualizations and to explore program trends. 

## Results: Tableau Visualziations and Descriptions
### Checkout Time for Users (Trip Duration)

![alt_text](https://github.com/NassimNatA/NY_Citibike/blob/main/Screen%20Shot%202021-01-09%20at%207.02.46%20PM.png)

Visualization of trip duration demonstrates that bike trips are significantly long with durations of 4-6 hours most frequent and highest frequency of 5 hours long. 

### Checkout Times by Gender 

![alt_text](https://github.com/NassimNatA/NY_Citibike/blob/main/Screen%20Shot%202021-01-09%20at%207.01.52%20PM.png)

When separating by gender, there are much higher number of bikesfor males (medium blue in image) compared to females. In addition, both genders show a peak of bike trips that extend 4-6 hours as exemplified by the previous image. 

### Trip by Weekday per Hours

![alt_text](https://github.com/NassimNatA/NY_Citibike/blob/main/Screen%20Shot%202021-01-09%20at%207.12.32%20PM.png)

A heat map generated for the bike trips by Weekday and per hour demonstrate that bikes are used most prominently on weekends, and on weekdays for commuting in the AM (to work: 6 AM - 9AM, from work: 5 PM - 6P M). 

### Trips by Gender (Weekday per Hour) 

![alt_text](https://github.com/NassimNatA/NY_Citibike/blob/main/Screen%20Shot%202021-01-09%20at%207.23.29%20PM.png)

A heat map of trip by gender show males are consistently with a higher number of records (i.e number of rides), but that females share the similar pattern of using bikes for commute during the AM (7 AM -9 AM) and PM (4 PM - 6 PM). 

### User Trips by Gender by Weekday 

![alt_text](https://github.com/NassimNatA/NY_Citibike/blob/main/Screen%20Shot%202021-01-09%20at%207.27.42%20PM.png)

A heat map of the trips by gender by weekday demonstrate that a majority of subscribers identify as male. This is anticipated since males have been shown in previous visualizations above to be the primary customer for bikeshares with the highest numer of bike rides acroos weekends, weekdays, and trip duration. 

## Bike rides by Age and Gender
![alt_text](https://github.com/NassimNatA/NY_Citibike/blob/main/Screen%20Shot%202021-01-09%20at%2011.23.33%20PM.png)

Total bike rides separated by age and filtered by gender show there is a peak of users at age of 30, after birth year of 1990 there is a decrease in users showing that older individuals do not invest in as many rides as younger users. Likewise, there is a peak of female users at the age of 51. 

## Closer look into Female bike users age of 51 
![alt_text](https://github.com/NassimNatA/NY_Citibike/blob/main/Screen%20Shot%202021-01-09%20at%2011.31.37%20PM.png)

A closer look into the distribution of bike usage for the female population peak at at 51 (born year 1969) show that a significant majority were no subscribers. This implies that there could have been a one-time event or sponsorship that caused a high population of female users to rent bikes compared to the drop out of users over the age of 30. 

## Summary

The data visualization above demonstrates that there are significant and consistent trends in bikeshares that support further investment into the program. Specifically, this program will be best utilized to support commute to/from school and jobs on Weekdays. Second, that male users will be most invested based on the current data that shows a singificantly higher usage than females. Third, this program will be most appealing for age group below 30, in which a drop out of bikeshares were seen to decrease after surpassing this age. An additional consideration would be to analyze the neighborhoods and locations in proximity to the bikeshare distribution since it can be expected that a male-populated, urban city will have the highest need for bikeshares based on these previous subscribers.

# Additional Visualizations

1. Map the starting and ending locations to a geograhical map to determine what locations are hotspots for bikeshares and determine if it differs by gender by filtering by Male/Female. 
2. Determine if a certain set of bikes are used more than others: graph bike id by counts and filter by gender to see if there are particular pieces of equipment more favorable than others per gender. 
