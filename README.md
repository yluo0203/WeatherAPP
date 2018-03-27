# WeatherAPP
Android_WeatherAPP

SJSU - In class project
Team: Tse-Jen Lu, Kang-Hua Wu

City View
  1.	Content
    Shows the following info about a city,  its current weather status,  and forecast
    a.	City Name
    b.	Day and Date of today; e.g., Thursday Oct 18
    c.	Weather status: Drizzle, Fog, etc.
    d.	Current temperature, highest, lowest, and
    e.	1 Day forecast every 3 hours, up to 24 hours, with weather status and temperature.
    f.	5 day forecast of daily weather, starting from next day, and showing the weather status around noon of each day, the highest and the lowest temperature of each day.
  2.	Navigation
    a.	If the info cannot be accommodated fully within one screen, please support scroll up and down.
    b.	Swipe left and right leads to next city or the previous city in the City List View. If you are at the beginning or end of list, do not support circular navigation.
    c.	You need to provide an up button in the action bar to navigate to the City List View. 
  3.	Support for the current city
    a.	If the current city view shows the city where you are in right now, the view needs to clearly indicate that, e.g., by adding text like “You are here now”. 

City List View
  1.	Shows a list of cities, where each city is rendered in a row, with info such as current local time of that city, city name, and current temperature.
  2.	Provide ways for the user to add and delete cities, one at a time.
    a.	When adding a city, please use Google’s place autocompletion widget here to support auto completion at city level.
    b.	Do not allow adding identical cities to the list.
    c.	Provide a convenient way for the user to add the current city.
  3.	Touch any specific city navigates the app to the City View.

Setting View
  1.	The Setting View allows the user to specify the following preferences
    a.	Fahrenheit (F) vs Celsius (C).
    b.	TBA

APIs to Use
Use the API at https://openweathermap.org/api for weather and forecast info.
Use Google’s place autocompletion API for city name autocompletion.

Target OS Version and Device: 
  a.	Target SDK version: Marshmallow (6.0) SDK Level 23
  b.	Minimal SDK version: Lollipop (5.0), SDK level 21
  c.	We will use a Marshmallow Nexus 6P emulator for grading purpose 
