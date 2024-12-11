Objective:
Build a weather dashboard using React that displays the current weather for the user’s searched city.

# Live: https://myweatherdashboard.netlify.app/

Features:
City Search:
Allow users to search for weather data by typing in a city name.
Display Current Weather:
Show the following weather details:
Temperature
Humidity
Wind speed
Weather conditions (e.g., sunny, cloudy) using icons or images.
Responsive Design:
Ensure the dashboard is fully responsive for both desktop and mobile devices.
Save Favorite Cities:
Allow users to save a list of their favourite cities to quickly view their weather data without searching each time.
Add a "Save" button next to the city search bar or current weather display.
Use local storage to save the list of favourite cities.
Display the saved cities as a clickable list or dropdown menu below the search bar.
Clicking on a saved city automatically fetches and displays its weather data.
Unit Conversion (Celsius/Fahrenheit):
Allow users to toggle between Celsius and Fahrenheit for temperature display.
Provide a toggle switch or button on the dashboard to switch units dynamically.
Update the current weather display to reflect the selected unit.

UI Elements:
Search Bar: Input field to enter the city name.
Weather Card: Display current weather in a card or section.
Icons or Images: Visual representation of weather conditions (e.g., sun, clouds, rain).
Saved Cities List: A clickable list or dropdown menu of favourite cities saved by the user.
Unit Toggle: A button or switch to toggle between Celsius and Fahrenheit.

Error Handling:
Display appropriate messages if the weather data can't be retrieved (e.g., city not found or API failure).

API: https://api.weatherapi.com/v1/current.json?key=${API_KEY}&q=${city}&units=metric

Sign Up and Obtain the API Key:
Visit WeatherAPI.
Sign up for a free account.
After signing in, navigate to the "My Account" or "Dashboard" section to obtain your API key.


Technologies:
React: For building the interface.
CSS or a CSS framework like Bootstrap or TailwindCSS for styling.
Axios or Fetch API for handling API requests.
Local Storage for saving favourite cities.
