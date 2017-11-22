# Bike-Sharing-Demand

INTRODUCTION
Bike sharing systems are a means of renting bicycles where the process of obtaining membership, rental, and bike return is automated via a network of kiosk locations throughout a city. 
Using these systems, people are able to rent a bike from one location and return it to a different place on an as-needed basis. Currently, there are over 500 bike-sharing programs around the world.

OBJECTIVES
●	To combine historical usage patterns with weather data in order to forecast hourly bike rental demand for the Capital Bikeshare program in Washington, D.C.
●	To help Capital Bikeshare better understand demand and allocate bike resources accordingly.

DATASET INFORMATION
The dataset was obtained from Kaggle and it provides hourly rental data spanning two years for the Capital Bikeshare program in Washington, D.C. 
It contains over 10,000 observations and 10 attributes. 

The data contains various attributes such as:
•	datetime - hourly date and timestamp
•	season - season 
o	1: winter
o	2: spring 
o	3: summer
o	4: fall
•	holiday - represents whether the day is considered a holiday 
•	workingday - represents whether the day is a working day 
•	weather - weather 
o	1: clear, few clouds, partly cloudy
o	2: mist + cloudy, mist + broken clouds, mist + few clouds, mist
o	3: light rain, light rain + thunderstorm + scattered clouds, light rain + scattered clouds
o	4: heavy rain + ice pellets + thunderstorm + mist, snow + fog
•	temp - temperature in Celsius 
•	atemp - feels-like temperature in Celsius 
•	humidity - relative humidity
•	windspeed - wind speed
•	count - number of total rentals

Submissions are evaluated on the Root Mean Squared Logarithmic Error (RMSLE). The RMSLE is calculated as

