# Weather-Explorer
Weather Explorer is a React web application that allows users to get real-time weather information for a specific location. Users can search for a city or place, and the app will fetch and display the current weather data, including temperature, humidity, wind speed, and more.

Features
Search for weather data of any location by entering the city or place name.
View real-time weather information, including temperature in Fahrenheit and Celsius, humidity, and wind speed.
Beautiful background image that changes based on the weather conditions.
Responsive design that adapts to different screen sizes.
How to Use
Clone or download this repository to your local machine.

Open the project in your preferred code editor.

In the terminal, navigate to the project directory.

Install the project dependencies by running:

bash
Copy code
npm install
Get an API key from OpenWeatherMap by signing up on their website (https://openweathermap.org/) and obtaining the API key.

Create a new file named .env in the root directory of the project and add the following line:

makefile
Copy code
REACT_APP_API_KEY=your_api_key_here
Replace your_api_key_here with the API key obtained from OpenWeatherMap.

Save the .env file.

Start the development server by running:

bash
Copy code
npm start
The app will be running at http://localhost:3000 in your web browser.

Enter the name of a city or place in the search bar and press the "Enter" key.

Weather information for the entered location will be displayed, including temperature, humidity, and wind speed.

Technologies Used
React: Frontend JavaScript library for building user interfaces.
Axios: HTTP client used to make API requests to OpenWeatherMap.
OpenWeatherMap API: Used to fetch real-time weather data based on the user's search.
