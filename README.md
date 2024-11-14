# city-weather-forecast-visualizer
MATLAB App Designer application that visualizes real-time and 5-day weather forecasts for selected cities using the OpenWeatherMap API.

**Requirements** 

***Accessing weather data requires a free OpenWeatherMap account.***

1. OpenWeatherMap Membership and API Key
2. API Key: Once registered, retrieve an API key from your account page. This key is essential for accessing weather data in the app.
3. Activation Delay: The API key may take 2-5 minutes to activate after registration. Wait if you encounter issues initially.
   
***Using MATLAB App Designer***

MATLAB App Designer will serve as the platform to design the user interface for selecting cities and displaying weather data.

***Writing Core Data Retrieval Function: fetchFiveDayForecast***
This function will handle API requests to OpenWeatherMap and retrieve city-specific weather data.

Function Requirements:
1. Data Retrieval: Connect to OpenWeatherMap using the API key to pull 5-day forecast data in JSON format.
2. Data Processing: Convert JSON data into a MATLAB-friendly format for further processing and visualization.
   
***Updating Graphs and Displaying Data***
The app should dynamically update its graphs based on the selected city, displaying relevant weather data.

1. Graph Update: Each time a city is selected, update the three graphs (temperature, humidity, wind speed) with new data.
2. Controls:
- "Get Information" Button: Retrieves current weather data for the selected city when clicked.
- "Add City" Button and Text Field: Allows users to type in a new city name and add it to the dropdown list. After adding, users can click "Get Information" to load weather data for this new city.
3. Forecast Data Display:
- Show the 5-day weather forecast for the chosen city on the graphs.
- Display the current weather conditions under each graph with descriptive labels for temperature, humidity, and wind speed.

![9](https://github.com/user-attachments/assets/514bcedd-ec75-4637-9d5c-d1f9138f0d71)
