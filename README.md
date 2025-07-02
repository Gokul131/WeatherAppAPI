🌦️ Emoji Weather App
A fun and visually engaging desktop weather application built with Python and PyQt5, using the OpenWeatherMap API to fetch real-time weather data and display it with expressive emojis and a user-friendly interface.
📦 Features
- 🔍 User inputs a city name to retrieve live weather data
- 🌡️ Displays the current temperature in Fahrenheit
- 🌈 Shows a weather description (e.g., clear sky, rain)
- 😎 Emoji representation of the weather condition
- 🚨 Detailed error handling with user-readable messages
- 🎨 Polished interface with styled labels and controls using Qt stylesheets
🛠️ Tech Stack
| Technology | Description | 
| Python | Programming Language | 
| PyQt5 | GUI Framework | 
| Requests | HTTP Client for API requests | 
| OpenWeatherMap API | Provides weather data | 


🚀 Getting Started
Prerequisites
Ensure you have the following installed:
pip install PyQt5 requests


Running the Application
- Clone or download this repository.
- Replace the api_key in get_weather method with your own from OpenWeatherMap.
- Run the script:
python weather_app.py


🌤️ Emoji Mapping
| Weather Condition | Emoji | 
| Thunderstorm (200–232) | ⛈️ | 
| Drizzle (300–321) | ☁️ | 
| Rain (500–531) | 🌧️ | 
| Snow (600–622) | ❄️ | 
| Fog/Mist (701–741) | 🌫️ | 
| Volcanic Ash (762) | 🌋 | 
| Squalls (771) | 🌬️ | 
| Tornado (781) | 🌪️ | 
| Clear (800) | ☀️ | 
| Clouds (801–804) | ☁️ | 


🧠 Error Handling
Gracefully handles and displays informative messages for:
- Invalid inputs
- API key issues
- Server/network errors
- City not found responses
✨ UI Preview
The window includes:
- A title bar labeled "Weather App"
- A centered input field and button
- Large weather emoji, temperature, and description display
Note: Fonts are styled using Calibri and Segoe UI Emoji for clarity and aesthetic consistency.


Let me know if you’d like to expand this with badges, screenshots, or contribution guidelines. You’ve got a fun and well-structured app here!
# WeatherAppAPI
