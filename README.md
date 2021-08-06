# PyBer Analysis
## Overview of Project
  - I have taken ride-sharing data from PyBer ranging from all types of city types: Rural, Sububurban, and Urban. I have compiled and created a summary DataFrame to show the relationship between types of city and number of drivers and average cost of the fare. This will help inform decisions at the company regarding improving access to ride-sharing services based on location, as well as help to determine affordability for under served neighborhoods. The line chart offers a clear visualization of the data by summing the weekly fares based on city type. 

## Results
  - First I used the pandas Groupby function to group my data by city type, then calculated the total rides, drivers, and fares for each city type. This allowed me to get the average fare per rider, and average fare per driver and organize them into a summary DataFrame to easily see the difference:

INSERT SUMMARY DF FOR DELIVERABLE 1

  - Looking at the summary DataFrame we can easily see that most of the rides came in the Urban city, with over 1,600 rides with an average fare of $24.53 per ride, while at the opposite end was the Rural city rides with only 125 rides, but with an average fare of $34.62. The suburban was in the middle of these two with 625 rides averaging $30.97 per ride. Looking at the fare per driver is interesting because there are only 78 drivers in the Rural areas compared to just over 2,400 in the urban areas which causes the average fare per driver in the rural areas to skyrocket to $55.49 compared to just $16.57 in the urban cities. From this summary, we can assume that each ride in the rural areas drivers make more per ride, but they don't get as many rides as the urban areas. It comes down to more rides with less profit per ride in the urban areas per driver VS less rides but a higher profit for the driver in rural areas (with suburban being right in the middle of both of these). 

  - Next I analyzed the total fares for each city type and summed them by week, and organized them into a visual line graph to show the relationship of total fares per week between the 3 different city types. We can see looking at the graph that Urban rides have the highest fare per week steadily, with suburban being the next highest, and urban coming in at the bottom. More rides are taken in the Urban city type resulting in a higher weekly summed fare every week from Jan 2019 to April 2019. The graph can be seen below:

INSERT LINE GRAPH HERE FOR DELIVERABLE 2

## Summary
  - This analysis will be very helpful to PyBer because we can see that less rides are taken as you get further out from the city, but those rides are for a higher fare and the driver gets more profit for longer rides than quick rides around the city. I can recommend that if you have drivers that want to maximize their profits for their rides, they should venture out to the rural parts of the city because longer rides result in more profit for them. As for the customer, if more drivers were able to go out to the rural parts of the city that would make the average fare come down and be more attractive so maybe we can get the weekly fare numbers up in the rural areas. It is important to not only serve the areas in high demand, like the urban areas, but also the rural areas to provide a service for the people out farther from town. If there was more drivers in their area offering a ride, more people would use the service and boost sales. This would also help even out the number of drivers in each area because as it stands now there are more than 30 times the amount of drivers in the Urban areas compared to the Rural.
 
 **I hope my analysis has helped in making decisions for PyBer moving forward to be the best ride-sharing app they can be!**
