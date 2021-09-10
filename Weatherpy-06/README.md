# WeatherPy with Python APIs
# module 6 Assignment


Summary 

Deliverable 1


Generate a new set of 2000 random latitudes and longitudes.
Get the nearest city.
Perform an API call with the OpenWeatherMap.
Retrieve the following information from the API call.
The latitude and longitude
The maximum temperature
The % humidity
The % cloudiness
The Wind speed
The Weather description, i.e., cloudy, fog, light rain, clear sky, etc.
Add the data to a new DataFrame.
Save the new DataFrame as a CSV file.



Deliverable 2


Filter the DataFrame using input statements for minimum and maximum temperature preferences.
Drop any empty rows on the new DataFrame.
Find the nearest hotel to each city using each city’s latitude and longitude and the Google Nearby Search.
Create a new DataFrame where the rows that do not have a hotel are dropped from the DataFrame created in Step 4.
Add the cities to a marker layer map with a pop-up marker for each city that includes:
Hotel name
City
Country
Current weather description and the maximum temperature
Export the DataFrame as a CSV file into the Vacation_Search folder as WeatherPy_vacation.csv.




Deliverable 3


Import the vacation CSV file.
From the map above with pick 4 cities that are in close proximity (on the same continent) that the customer would travel to and create a directions layer map.
For the "travel_mode" use either "DRIVING", "BICYCLING", or "WALKING".
Take a screenshot of the route and save it.
Then create a marker layer for the four cities. Each city will should have a pop-up marker that contains
The hotel name
The city
The country
The current weather description and the maximum temperature



Analysis



City_ID                392
City                   392
Country                392
Lat                    392
Lng                    392
Max Temp               392
Humidity               392
Cloudiness             392
Wind Speed             392
Current Description    392


	Aksu	CN	82.42	clear sky	41.12	80.26	
7	Touros	BR	80.60	broken clouds	-5.20	-35.46	
10	Morehead	US	75.20	clear sky	37.27	-87.18	
11	Port Elizabeth	ZA	84.20	clear sky	-33.92	25.57	
16	Northam	GB	82.40	few clouds	51.03	-4.22	
18	Hyderabad	IN	87.01	haze	17.38	78.47	
20	Port Alfred	ZA	82.00	clear sky	-33.59	26.89	
22	Atuona	PF	79.72	clear sky	-9.80	-139.03	
23	Kapaa	US	73.40	heavy intensity rain	22.08	-159.32	
25	Nikolskoye	RU	88.00	clear sky	59.70	30.79	