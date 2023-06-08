# Citi Bike Analysis with Tableau

![image](https://github.com/Marce1301/City_bike/assets/119386031/6d1d3128-b53e-4c5b-bb47-1881e9679400)

Congratulations on your new job! As the new lead analyst for the New York Citi Bike program, you are now responsible for overseeing the largest bike-sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have questions about the program, so your first task on the job is to build a set of data reports to provide the answers.

# Deployment
Please find below the link to the Tableau dashboard, showcasing the results of the analysis: 
https://public.tableau.com/app/profile/marcela.maldonado/viz/Challenge_Tableau_16848170446450/Historia1?publish=yes

# Instructions
Your task in this assignment is to aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena.

* Design 2–5 visualizations for each discovered phenomenon (4–10 total). You may work with a timespan of your choosing. Optionally, you can also merge multiple datasets from different periods.

* Use your visualizations (not necessarily all of them) to design a dashboard for each phenomenon. The dashboards should be accompanied by an analysis explaining why the phenomenon may be occurring.

Create one of the following visualizations for city officials:

* Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey, with zip code data overlaid on top.

* Advanced: A dynamic map that shows how each station's popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

Create your final presentation:

* Create a Tableau story that brings together the visualizations, requested maps, and dashboards.

Ensure your presentation is professional, logical, and visually appealing.

# Data Source

The data that I used to work in this project was retrived from : https://citibikenyc.com/system-data and I choose data from New York bike stations in the period of december 2022 , because I belive this is a time of year where New York is very crowded because of the holidays and also is a very nice period to analyse.

## Results
For this Tableau Visualization challenge I create a History comoposed by 6 dashboards and 2 visualization maps.

# Dashboards

* Map Visualization
![image](https://github.com/Marce1301/City_bike/assets/119386031/8bf5ba00-7865-4527-b60e-40243844944c)
Here we can figure out all the citi bike stations with travels in the period of December 2022 in New York City.
In each station we can find the emergent description of the postal zip code loaction, citi bike station name and citi bike station ID.

* Top 10 station map visaulization.
![image](https://github.com/Marce1301/City_bike/assets/119386031/aad9d579-6c7f-433d-975a-149c79e1489f)
Here we can figure top10 citi bike stations based on the end station Ride Id numbers. We can see that the top stations are near Central Park , Broadway,  Rockefeller and Empire State. 
In each station we can find the emergent description of the postal zip code loaction, and citi bike station name.

* Hourly dispersion dashboard.
![image](https://github.com/Marce1301/City_bike/assets/119386031/62cec04b-8de0-4a18-bd40-e8f9b2af1fe8)
In this dashboard I created an hourly heat map by day of the week where we can see the number of rides per hour per day of the week .
We can see that 8 am and 5- 6 pm are the rush hours to take where the biciles are more used. By day with more rides is Thursday.

* Distribution per day of the week.
![image](https://github.com/Marce1301/City_bike/assets/119386031/dce0f943-3f8d-4001-8ed3-082a8e31026b)
In this dashboard I created 3 bar graphics where we can see the dispertion of number of rides per day of the week. 
In one chart I added the distribution per ridable type (Classic, electric) and in other chart I added the dispersion of member-casual user. 

* Station Analysis.
![image](https://github.com/Marce1301/City_bike/assets/119386031/84383338-93c0-4b29-8085-a9ff0a2b4998)
Making a relation of the number of trips given the top 10 departure stations to the top 10 ten ended stations, we can see that the station with the major ride Id numbers is Broadway and W58 that is a central station to enter central park or walk into Broadway or take Columbus circle subway that also is a conection Subway station.

* Start and end stations trip distribution analysis.
![image](https://github.com/Marce1301/City_bike/assets/119386031/419f724b-1120-41d3-a4c5-7fdfe970f38c)
In this dashboard we can apreciate in total which are the stations with the major number of trips. 
by start station we can see that East 33 & 1st Ave is the top start station. And 6th Ave & West 33rd Street is the top end station , Near this station is loacated the Empire State which is an icon of New York.

* Averge trip duration.
![image](https://github.com/Marce1301/City_bike/assets/119386031/a263ebdf-72e0-4dfd-821c-c0ff364e3ea8)
Here we can see the average time per trip in minutes. I made the dispersion per hour of the day and surprisely the result indicate that starting in the blocking hour of 3:00 - 4:00 am  is when the trips register the maximum duration. This could be because in other time slots the average is degraded by near 0:00 mins movements due to change of bicicle or change of mind when taking a bicicle . Also the 3:00 am slot could be the one with the higher average because at that hour is when people usualy returns home from social events. 

Also I made a visualization to see Average trip duration by week day and where we can see that sunday is the day that has trips with higher average trips.


# Conclusion

In conclusion, this Tableau analysis provides a comprehensive overview of the trends and patterns in Citibike usage over a specified time period ( December 2022) Through the creation of interactive dashboards and visualizations, key insights have been extracted and presented, highlighting trends in user type as well as trip patterns based on hours and weekdays.




