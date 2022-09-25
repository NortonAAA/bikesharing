# Bike Sharing NYC Analysis Report
Tableau Module 14

## Overview of Statistical Analysis
The purpose of this analysis was to review existing data for New York City bike sharing program and find if there was any viability to establish a similiar program in Des Moines.

## Results
The results will be described and images below. For full Tableau Story please go to [Andrew's Tableau Story](https://public.tableau.com/views/BikeShareChallenge_16639890198640/BikeShareChallengeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

### Summary Statistics
While not nearly the booming metropolis that is New York City, using some of the data, there is a good opportunity a bike sharing program. One of the initial statistics is the distribution of gender. Per the [US 2020 Census](https://www.census.gov/quickfacts/fact/table/newyorkcitynewyork,desmoinescityiowa/SEX255221), New York City has as 52.3% Female population while Des Moines has a 50.9% Female population. 
Based on the summary statistics in this dataset, that gives a slight edge in the market where Male riders are a significantly larger pecentage of the ridership.

![](https://github.com/NortonAAA/bikesharing/blob/main/images/summary_stats.png)

### Riders by Time of Day
![](https://github.com/NortonAAA/bikesharing/blob/main/images/Rides_by_24hours.png)

New York City is the city that never sleeps but the main profile of hours reflects a pretty standard work week by day. This even includes the main commute times of 8-10 am and 5-6 pm. This give opportunities for maintenance of the bikes in off peak times. In Des Moines, the shift to start pulling bikes could start earlier in the evening around 8 or 9 to get most redeployed by the morning.

### Distribution of Trips by Starting Location
![](https://github.com/NortonAAA/bikesharing/blob/main/images/Top_Starting_Locations.png)

A zoom in of Lower Manhattan shows the highest areas of starting locations. Manhattan definitely has some key spots around tourist areas but includes enough distribution in the total areas to serve the workforce. This would be ideal to identify areas in Des Moines (such as historic downtown or the many parks) to locate the majority of bikes.

### Trip Duration Summary and by Gender
![](https://github.com/NortonAAA/bikesharing/blob/main/images/Tripduration_summary.png)
![](https://github.com/NortonAAA/bikesharing/blob/main/images/Tripduration_by_gender.png)

The majority of the trips occur for less than 30 minutes so any given trip doesn't tie up a specific bike for too long with the size of Manhattan vs. Des Moines should allow for quick turn around of each bike assest. This summary is also the first breakout by gender and we can see the difference between Male and Female where Males are a larger part of the overall rides.

### Trips by Weekday Summary and by Gender
![](https://github.com/NortonAAA/bikesharing/blob/main/images/Trips_by_Weekday_together.png)

The above visualizations shows that the majority of the trips occur during the typical 8am-5pm workweek. Breaking out the summary by gender we see a similar break between genders of Male and Female. However both groups still focus during the typical commute.

### Category of User Trips
![](https://github.com/NortonAAA/bikesharing/blob/main/images/User_trips_by_gender_by_weekday.png)

Based on the above visualization, there is a good basis for a Subscriber model where usage is much higher than just the general walk up customer. A specific callout is that the Subscribers are heavily distributed in the work week, while the normal walk up customer shows a slightly higher distribution on the weekends. This provides for a heavily sales volume on the work week but ability to capture some more customers on weekends.

### Individual Bike Usage
![](https://github.com/NortonAAA/bikesharing/blob/main/images/Distribution_by_Bikeid.png)

The distribution of utilization of Trip time is fairly concentrated in a small percentage of the bikes. This gives an opportunity to scale to a smaller marker like Des Moines and focus the maintenance on those assests with the highest usage.

## Summary
There is a big market in New York City but there is a good opportunity to introduce in Des Moines. The basis of a work week and gender percentages doesn't make Des Moines different. Also, looking at the above data, there is an opportunity to start up with fewer bikes overall to focus ridership. The key will be a good balance of placement and encouragement of a Subscriber model that makes repeat customers possible.
