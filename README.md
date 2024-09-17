Weather App 🌦️

This Weather App is a simple web application that allows users to search for current weather information in any city worldwide. The app makes use of the OpenWeatherMap API to fetch weather data and display it on the page.

Features ✨

. Fetches real-time weather data using the OpenWeatherMap API.

. Displays the city name, country code, temperature, weather condition, and an icon representing the weather.

. Avoids duplicate entries by notifying the user if the weather for a city has already been displayed.

. Provides a friendly user experience with validation messages.

Technologies Used 🛠️

. HTML: For structuring the webpage.

. CSS: For basic styling.

. JavaScript: For handling the user interface interactions, API calls, and rendering data.

. OpenWeatherMap API: Used to fetch real-time weather data for cities around the globe.

Setup & Installation 🖥️

1. Clone the repository:
  git clone https://github.com/your-username/weather-app.git
  cd weather-app

3. Obtain an API key:

  . Sign up at OpenWeatherMap and get an API key.
  
  . Replace the placeholder apiKey in the JavaScript file with your API key:
  
     const apiKey = "YOUR_API_KEY_HERE";
     
5. Run the application:

     . You can simply open the index.html file in a browser to use the app.
   
Usage 🚀

1. Open the app and type the name of a city into the search bar.

2. Hit "Enter" or click the submit button to fetch the current weather.
 
3. The app will display the city name, country, temperature in Celsius, weather description, and a corresponding weather icon.

4.  If you enter a duplicate city, the app will prompt you to enter a new city or specify the country.
 
Error Handling 🚧

. If an invalid city name is entered, the app will display a message: "Please search for a valid city 😩".

. If the city is already in the list, the app will notify the user: "You already know the weather for this city."

Future Enhancements 🛠️

. Add support for additional weather details like humidity, wind speed, etc.

. Enable location-based weather retrieval.

. Add unit conversion between Celsius and Fahrenheit.

