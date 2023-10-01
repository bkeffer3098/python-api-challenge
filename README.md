# python-api-challenge

Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
This repository includes my exploration of the OpenWeather Api as well as Geoapify. WeatherPy is a Python program that pools a random amount of cities around the world and captures details such as latitude, longitude, max temperature, humidity %, etc. Using WeatherPy and matplotlib, correlations between several different details were analyzed. These charts are included in the output_data folder. In further analysis, correlation of these weather facets is displayed in both the Northern and Southern Hemispheres. Analysis of the correlation is provided within the Jupyter files. 

VacationPy, located within the WeatherPy directory, runs as a companion to the WeatherPy program, utilizing a CSV file that is made from WeatherPy. Within this program, Geoapify is explored to make a map that displays the cities chose from WeatherPy and their Humidity percentage controls the size of their dot on the map. Further exploration allows the user to choose ideal vacation weather and narrow down the number of cities seen. From there the program continues on to find the first hotel within 10,000 meters of the specific city. This would allow users to know what kinds of locations are places they could stay with their own ideal weather. 
