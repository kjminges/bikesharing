# Module 14 Assignment - NY Citibike 

## Background
In an effort to further convince investors that a bike-sharing program similar to NYC's Citibike would be feasible in a city like Des Moines, Iowa, my team and I have put together a bike trip analysis that reviews recent Citibike data. Our analysis is accompanied by a Tableau story which can be viewed by using the link below. We will be referencing this story throughout our analysis.

[link to story](https://public.tableau.com/shared/XCDGB265R?:display_count=n&:origin=viz_share_link "link to story")


## NYC Citibike Analysis
After parsing through the Citibike data for the month of August 2019, we were able to create various diagrams which will help explain the main use of Citibikes in NYC: commuting. If Des Moines focuses on using a bike-share program to encourage a more sustainable commuting method, it will help finance the program and likely lead to more leisurely uses outside of traditional work hours (Monday through Friday, 8am through 6pm). In the list below, we will take you through the pages of our Tableau story:

1. Citibike rides based on duration: These line graphs review the number of rides (y-axis) based on the duration of the trip (x-axis ranging from 0 to 180 minutes)
- Almost all riders use Citibikes for trips lasting under 1 hour. A large majority of them don't even ride for more than 30 minutes. This would suggest that the riders typically using this for specific trips from one point to another and not for sightseeing, or multi-point trips.
- When we look at this data split out by rider gender, the distribution does not change. What does become evident is that men are using Citibike at a much higher rate then women. This could possibly be due to differing risk tolerances.

2. Citibike rides by weekday: This page has a variety of heat maps which look at the distribution of rides based on the day of the week in which they occured
- The orange/red charts show the distribution based on the day of the week (x-axis) and the time of day (y-axis). The one located on the top breaks it out further by gender. What these charts tell us is that a majority of rides occur during work week days (Monday through Friday) typically around the beginning of the day (7am-10am) and the end of the work day (5pm to 8pm). The timing of these rides would suggest that people are frequently using Citibike for commuting purposes. 
- During the weekdays, the number of rides is less concentrated on a couple of hours and more consistent throughout the day (9am to 9pm). This would suggest that weekend riders are using it more for their leisure and possibly for sightseeing and for a convenient and fun way to get to where they are going.
- Finally, the blue chart in the bottom right of the page shows the distribution of rides based on gender (x-axis) and day of the week (y-axis). The day of the week is further split out based on the usertype (i.e. are they a subscriber or not). This chart further helps our analysis above. Most rides are taken by subscribing ment during the work week. One could argue that commuters would certainly be subscribers since they would be using the service with such frequency that it becomes more cost efficient to subscribe.

3. Citibike rides by station:
- Finally, the last page reviews the distribution and density of trips based on the station the trip originated from (left map) and the station the trip ended on (right map). The darkness of the color and the radius of the circle indicates the frequency of trips. Visually, these maps are almost identical. This also helps argue that commuting is the main form of use for Citibike. Commuters will typically ride both to and from work. This means that there are equal rides going to and from each station, causing the maps to look similar. 


## Conclusion
We believe that it is clear that the main use of NYC's Citibikes are for commuting purposes. Giving people a commuting alternative that is also eco friendly would not only be a PR win but would be a profitable business as well. While the main strategy would be to promote the bike-share program for commuting, the money from subscribers and work-weekday rides would help supplement the more leisurly riding that would mostly occur on the weekends. This would also help the local economy as it promotes movement and tourism throughout the city. 

In order to understand how bikes move from station to station and the amount of human assistance that may occur (i.e. paid employees who move bikes from overcrowded stations to less crowded stations), we will want to look at the net number of bikes that typically flow through a station. Where are the stations with a high influx of bikes and where are the ones that tend to sit empty (bar chart with the stations on the y axis and the net bikes over the course of a month on the x axis). Once we have a better understanding of this, we can even view the density of rides from station to station (a heat map with start station on the x axis, end station on the y axis, and the count for bikes as the color density). Is there an opportunity to strategically place stations to avoid having to manually move bikes from station to station. 