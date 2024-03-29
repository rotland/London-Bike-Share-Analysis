# London-Bike-Share-Analysis
  ![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/c5605f79-3ca9-47d8-bd89-f5cdc00498c4)

 Exploratory data analysis (EDA) was performed on Historical data for bike sharing in London to find out if weather, season, holidays and other such variables have any effect on number of bike user. 
 
Our analysis in question was carried out with python and Excel. python library was used to gather data from kaggle. i also explore, assess and manipulate the data using the pandas library in python.

check out my python code here: https://github.com/rotland/London-Bike-Share-Analysis/blob/main/London_Bike_Share_Analysis_From_Data_Gathering_to_Visualization.ipynb

The final step involves creating impactful visualization using excel to bringing all the insights together.

Santander Cycles or (Boris Bikes) is London's self-service bike-sharing scheme for short journeys. The scheme is sponsored, with Santander UK being the main sponsor from April 2015.
The scheme commenced operations as Barclays Cycle Hire on 30 July 2010 with 5,000 bicycles and 315 docking stations distributed across the City of London area and parts of eight London boroughs.

check more about Santander Cycles: https://en.wikipedia.org/wiki/Santander_Cycles
![image](https://github.com/rotland/London-Bike-Share-Analysis/assets/65259178/4da37321-3e60-4caa-973a-eda64b353889)

# Dataset Used:
Historical data for bike sharing in London ‘Powered by TFL Open Data’ from Kaggle. The datasets contain data from year 2015 to 2016 with 17414 rows & 10 columnns for every hour of the year.

https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset

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
