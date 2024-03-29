# London-Bike-Share-Analysis
  ![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/c5605f79-3ca9-47d8-bd89-f5cdc00498c4)

 Exploratory data analysis (EDA) was performed on Historical data for bike sharing in London to find out if weather, season, holidays and other such variables have any effect on number of bike user. 
 
Our analysis in question was carried out with python and Excel. python library was used to gather data from kaggle. i also explore, assess and manipulate the data using the pandas library in python.
The final step involves creating impactful visualization using excel to bringing all the insights together.

check out my python code here: https://github.com/rotland/London-Bike-Share-Analysis/blob/main/London_Bike_Share_Analysis_From_Data_Gathering_to_Visualization.ipynb

Santander Cycles or (Boris Bikes) is London's self-service bike-sharing scheme for short journeys. The scheme is sponsored, with Santander UK being the main sponsor from April 2015.
The scheme commenced operations as Barclays Cycle Hire on 30 July 2010 with 5,000 bicycles and 315 docking stations distributed across the City of London area and parts of eight London boroughs.

check more about Santander Cycles: https://en.wikipedia.org/wiki/Santander_Cycles
 
 # Metadata:
"timestamp" - timestamp field for grouping the data

"cnt" - the count of a new bike shares

"t1" - real temperature in C

"t2" - temperature in C "feels like"

"hum" - humidity in percentage

"wind_speed" - wind speed in km/h

"weather_code" - category of the weather

"is_holiday" - boolean field - 1 holiday / 0 non holiday

"is_weekend" - boolean field - 1 if the day is weekend

"season" - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter.

"weathe_code" category description: 1 = Clear ; mostly clear but have some values with haze/fog/patches of fog/ fog in vicinity 2 = scattered clouds / few clouds 3 = Broken clouds 4 = Cloudy 7 = Rain/ light Rain shower/ Light rain 10 = rain with thunderstorm 26 = snowfall 94 = Freezing Fog

 # Data Cleaning
Data cleaning & manipulation was done using python, python library was used to gather data from Kaggle. I also explore, assess and manipulate the data using the pandas library in python.
Finally, write the final data frame to an excel file that I used in my visualizations.
Check out my data cleaning & manipulation process in google Collab:
https://colab.research.google.com/drive/1m454ewILZR7ijqAckQCbgNPlGf6AbIot?usp=sharing

 # Analysis
Part 1:
This analysis shows the general statistics for London bike share dataset, by using excel to visualize the bike usage by seasons, months, weeks (weekdays & weekends), holidays & non-holidays and hours of the day.

 # Total Number of Riders by Weekdays 
Total Number of Riders by Weekdays 
Monday, Tuesday, Wednesday & Thursday show the highest number of riders, while the number of riders is much lower in the weekend. people use bike mostly during weekdays i.e., to & from work.

 ![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/96616ca8-0cb0-47bd-8b41-9d7e27158e60)

 # Number of Bikes Used on Weekdays & Weekends
About 76% of the total bikes have been used on weekdays & 24% were used on weekends
 
![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/d4fb9957-362d-4f91-8545-31619fa52b01)

 # Bikes used on Holidays vs non-holidays.
Almost 99% of the total bike was used on non-holidays, while about 1% were used on holidays.
 
![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/807bc12f-b98e-4eef-8469-a125aa9c258d)

# Number of Bikes on Holidays for the Year 2015
The bars show the total number of bikes used for particular holiday. Spring bank holiday show the highest number of bikes used, it is a day off work for most people in London, businesses & organization.

 ![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/e20a52ff-1d9b-48e1-89f9-5beae9fb123c)

 # Riders Hours of the Day and Bike
 8 AM & 5 PM shows the highest number of bike riders, which correspond to the time that people go to & from work. 

  ![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/484232f4-a115-49a4-acba-093d861062b6)

 # Bike used on weekends in various seasons.
Summer had the highest number of bike users on weekends than any other seasons.
 
![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/a02329f9-1c20-41c2-859a-1fd712db500f)

From our analysis People used the bikes mainly for work commutes but as can be seen from the graphs on weekdays, many people used them mostly from 8am and 7pm, people also used them for leisure as weather gets better in the weekend.

 #  Part 2:
Investigating the effects of season, weather, temperature, humidity and wind speed over the bike usage.
Riding bike is an outdoor activity and naturally it is affected by weather and seasons equally. As a summer morning will draw more people out than a rainy or snowy day, it is important to consider the effect of seasons as well.


 # Number of Riders in Four Seasons
Around 3.2million people used London bike service in summer months alone, followed by 2.43million in Autumn and 2.4million in Spring, Winter shows the lowest number of riders in 2015 -1.69million

![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/14f5da1e-e325-4a05-8b9a-85b28b18d319)

 # Effect of humidity and windspeed on number of bike riders 
For most past of the year, London has a humidity between 50% - 80% which means there is high chance of precipitation. Number of bike riders gradually increase when the weather is clear as seen from the chart. Number of bikes change with humidity, windspeed, temperature and weather.

 ![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/748022c7-d6c7-4ada-b8f9-6845e2f6f52c)
 
Graph showing relation between humidity, windspeed and number of bikes used on a clear day.

Humidity has negative correlation with bike usage. As humidity in the air increases, the number of bikes usage reduces gradually when the weather is rainy or broken cloud.

 ![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/d486e6da-1f5b-48bf-9ddc-9abe295d285d)

 Graph showing relation between humidity, windspeed and number of bikes used on a broken cloud day.

  ![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/cd3a2fb2-af1b-49af-8853-a9a58d30bf86)
  
Graph showing relation between humidity, windspeed and number of bikes used on a rainy day.  

![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/4ea57720-5881-4db1-97d9-bc7dd9e51150)

Graph showing relation between humidity, windspeed and number of bikes used on a snowy day.

 # Relation between Temperature and Number of Bikes 
The bar chart shows the total number of riders for each month and the line chart shows the average temperature. As temperature increases so does the number of riders. It seems temperature has a positive correlation with number of riders.

![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/18621c67-90cb-4776-a68d-04c560a62d2c)




