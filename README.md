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
