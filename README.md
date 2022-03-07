# **bikesharing**
# **NY Citibike with Tableau** 

## **Overview of the statistical analysis** 

* Last summer you and your friend Kate took a trip of your lifetime to New York City for two full weeks. Exploring Historical landmarks like Central Park, Statue of Liberty and the Empire state building. It was a magical experience and when you get home and look through your vacation pictures and has a realization. You and Kate had biked everywhere which allowed to really get to know the city and interact with the people who live there. An idea if you can start similar bike sharing business in your hometown Des Moines forms in your mind. Kate has a potential angel investor who might be interested in providing funding to explore a bike sharing program in Des Moines. The first step is to figure out how bike sharing business actually works in New York City.
* In this challenge we will analyze the Citi Bike data for New York City and create visualization to convince investors that a bike-sharing program in Des Moines is a solid business proposal. We will also create a story and bike trip analysis for the stakeholders.

### Purpose 
* to Change Trip Duration to a Datetime Format and create a set of visualizations to
	- the Checkout Times for Users Viz
	- the Checkout Times by Gender Viz
- the Trips by User Weekday for Each Hour Viz
- the Trips by Gender (Weekday per Hour) Viz
- the User Trips by Gender by Weekday Viz
	- As well create a story and a written summary for the Bike trip Anaysis.

## **Results** 

* Total Rides
![Total Rides](./Datasources/Total_rides.PNG)
* This is the total number of bike rides 

* Top Starting locations
![Checkout Times](./Datasources/Top_Starting_Locs.PNG) 

* The above map shows most popular locations for starting bike journey or trips. The darker and larger the circle means more stations and more tourists. This helps us identify the highest-traffic locations. 

* Top End locations
![Checkout Times](./Datasources/End_locations.PNG)

* This map above shows the most popular locations for bike drop off locations. The darker(red) and larger the circle means the more stations in that location. 

* Checkout Times for Users
![Checkout Times user](./Datasources/Checkout_Users.PNG) 

* the above viz shows the length of time that bikes are checked out for all users. The number of bikes checked out are highest for trip duration less that 25 minutes. 

* Checkout Times by Gender
![Checkout Times Gender](./Datasources/Checkout_Times_Gender.PNG) 

* the above viz shows the length of time that bikes are checked out by gender. The Orange line shows that the highest number of bikes are checked out by Male for most active trip duration which is less 25 minutes. Next is blue line which are female riders. 


* Trips by Weekday for each Hour
![Trips by Weekday Hour](./Datasources/Trips_Weekday_Hour.PNG) 

* the above viz shows the number of bike trips for all riders for each hour of each day of the week. The peak hours for bike trips during the month of August are from 5 pm - 7 pm for weekdays. For Saturday the number of bikes checked are high from 11 am - 3 pm.

* Trips by Gender Weekday per Hour 
![Trips by Gender](./Datasources/Trips_Weekday_Hour_Gender.PNG) 

* the above viz shows the number of bike trips for each hour of each day of the week by Gender. The number of bike trips are highest for male during peak times 5 pm - 7pm and 8 am – 9 am. Also The highest numbers of bike trips are on Thursday and Friday, followed by Monday and Tuesday for same active hour.
* Trips by Gender Weekday per Hour 
![Trips by Gender](./Datasources/Trips_Weekday_Hour_Gender_Usertype.PNG) 

* the above viz shows the number of bike trips for each day of the week by Gender and Usertype. Thursday and Friday have highest number of bike trips by Male subscribers, followed by female. We have also seen in the module; younger riders tend to use the bikes for longer periods of time. Mondays and Tuesdays have second highest number of bike trips by Male Subscribers.

# Link to NYC Citibike Story
[CibiBike Visualization](https://public.tableau.com/authoring/CitiBike_Visualization_16465293946870/NYCCitibikeStory#1)

## **Summary** 

* In conclusion, the most active hours are from 5pm to 7 pm or 8 am in the morning. It may be people are coming from work or going to work. Also, tourists are active around that time. Thursday and Fridays are the busiest days of the week followed by Monday and Tuesday. We have also seen that the length of time where highest number of bikes are used is less 25 minutes (trip duration). The highest number of bikes are checked out by Male Subscribes. Then followed by female subscribers and then by unknown.We also seen the most popular stations for the bike starting and drop off location. This will help to convince investors that a bike-sharing program in Des Moines would work and is a solid business proposal.
* two additional visualizations are suggested for future analysis
	- bike maintenance will likely be one of the biggest expenses. So, we can include visualization to determine the bikes due for repair. We also know that from our visualization earlier pick hours are either 8 - 9 am and 5 - 7 pm, so the best time to maintain bikes would be from 2am - 5am. 
	- The other visualization would be to include weather (rain, wind). we know that we do not have weather information in our data. For e.g., to know how weather(rain) affects peak ride hours or it has no effect. 
	- Another visualization would be include other months since the data we have is just for August. We would like to know if August is most active month in comparison with other months. 
 






