## Bikesharing ##

[NY City Bikeshare dashboard](
https://public.tableau.com/app/profile/shyam.patel8801/viz/NewYorkCitiBankStory_16671203551890/Story1)

<p align="center">
 <img width="400" height="300" src="https://github.com/shyampa95/bikesharing/Images/image%2012.jpg">
</p
  
In order to explore the sustainability of a bike-sharing business in Des Moines, the project uses data visualisation tools to offer an analysis of New York Citi Bike data to investors. I used Pandas to convert the "tripduration" column from an integer to a datetime datatype for this study. 
    
Using the converted datatype to create a set of visualizations to demonstrate the following:
 
   •	Illustrate the length of time that bikes are checked out for all riders and genders
 
   •	Illustrate the number of bike trips for all riders and genders for each hour of each day of the week
 
   •	Illustrate the number of bike trips for each type of user and gender for each day of the week.
 
   • Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.
 
<p align="center">
  <img width="400" height="300" src="https://github.com/shyampa95/bikesharing/Images/image%209.png">
</p>
 
 

###  New York Citi Bike data visualizations for August 2019

   1.	Change Trip Duration to a Datetime Format
      Using Python and Pandas functions, the "tripduration" column was converted from an integer to a datetime datatype to get the time in hours, minutes, and seconds                   (00:00:00).
  
<p align="center">
<img width="600" height="300" src="https://github.com/shyampa95/bikesharing/Images/Image%201.png">
</p>


  2.	Length of time that bikes are checked out for all riders

<p align="center">
<img width="600" height="400" src="https://github.com/shyampa95/bikesharing/Images/image%202.png.Length%20of%20time%20that%20bikes%20are%20checked%20out%20for%20all%20riders.png">

  3.	Create the Checkout Times for Users   
     •Bikes are checked out for ~ 4 to 6 hours.
 

</p>
<p align="center">
<img width="800" height="400" src="https://github.com/shyampa95/bikesharing/Images/image%203.png">
</p>


   4.	Create the Checkout Times by Gender  
      •	Male users take approximately 3 times more rides than the female users.

<p align="center">
<img width="800" height="400" src="https://github.com/shyampa95/bikesharing/Images/image%204.png">
</p>


5.	Trips by Weekday for Each Hour

<p align="center">
<img width="400" height="400" src="https://github.com/shyampa95/bikesharing/Images/image%205.png">
</p>


6.	Trips by Gender (Weekday per Hour)

    •	Most weekday rides are around 7:00 AM to 9 AM and 5:00 PM to 7:00 PM.
    
    •	Weekend rides are highest from 10:00 AM to 7:00 PM.
    
    •	Those rides are mostly taken by male users.

<p align="center">
<img width="800" height="500" src="https://github.com/shyampa95/bikesharing/Images/image%206.png">
</p>


7.	User Trips by Gender by Weekday 

<p align="center">
<img width="400" height="400" src="https://github.com/shyampa95/bikesharing/Images/image%207.png">
</p>


8. Top Starting Locations

   •	There were over 2.3 million rides for the month of August 2019.

   •	81% of the users were subscribers. 65% of the users were confirmed males and 25% were confirmed females.

   •	There is a wide range of the age of the users. Younger users tend to use the service for longer rides.

   •	Top ride starting locations are in the most touristic and busy areas, as we see here in Manhattan.

<p align="center">
<img width="800" height="400" src="https://github.com/shyampa95/bikesharing/Images/image%208.png.jpg">
</p>

   9.	 August Peak Hours
   
   •	The busiest times, from 5:00 PM to 7:00 PM, call for the most resources to be activated.
      
   •	The activity from 2:00 AM to 5:00 AM is low so this would be the window for bike maintenance.


<p align="center">
<img width="800" height="400" src="https://github.com/shyampa95/bikesharing/Images/image%2011.png">
</p>


10.	Bike Utilization

<p align="center">
<img width="400" height="400" src="https://github.com/shyampa95/bikesharing/Images/image%2010.png">
</p>


#### Summary ####

   • The data indicates that New York's bike-sharing programme was very active in the month of August 2019..

   Additional analysis would be beneficial by :
      
   • comparing data for different months to determine trends across the year.
    
   • including weather data to find the correlation between the weather and the rides.
