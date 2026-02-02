# Weather App

**Tier:** 1-Beginner  

A weather app is the perfect introduction to working with external APIs and real-world data.  
In this project, you'll create a **Weather App** that fetches and displays current weather information for any city worldwide.  

This project teaches **API integration**, **asynchronous programming**, and **data presentation** — crucial skills for modern web development.


## Features

- **City Search** – Search for weather in any city worldwide.  
- **Current Weather** – Display temperature, conditions, and weather description.  
- **Weather Icons** – Show appropriate weather icons for different conditions.  
- **Location Detection** – Get weather for user's current location.  
- **Temperature Units** – Toggle between Celsius and Fahrenheit.  
- **Loading States** – Show loading indicators while fetching data.  
- **Error Handling** – Handle network errors and invalid city names.  
- **Responsive Design** – Works perfectly on mobile and desktop.  


## User Stories

- [ ] User can see a **search input field** to enter city names.  
- [ ] User can **search for weather** by typing a city name and pressing Enter or clicking Search.  
- [ ] User can see **current temperature** displayed prominently.  
- [ ] User can view **weather conditions** (sunny, cloudy, rainy, etc.) with appropriate icons.  
- [ ] User can see **additional weather details** (humidity, wind speed, pressure).  
- [ ] User can **toggle temperature units** between Celsius and Fahrenheit.  
- [ ] User can **get weather for current location** using a geolocation button.  
- [ ] User sees **loading indicators** while weather data is being fetched.  
- [ ] User sees **error messages** for invalid cities or network issues.  
- [ ] User can **refresh weather data** with a refresh button.  


## Bonus Features

- **5-Day Forecast** – Display weather forecast for the next 5 days.  
- **Weather Maps** – Show precipitation or temperature maps.  
- **Recent Searches** – Save and display recently searched cities.  
- **Weather Alerts** – Show severe weather warnings if available.  
- **Sunrise/Sunset Times** – Display sunrise and sunset times.  
- **Air Quality Index** – Show air quality information for the location.  
- **Theme Changes** – App theme changes based on weather conditions.  
- **Offline Support** – Cache last searched cities for offline viewing.  


## Learning Outcomes

- **API Integration** – Fetch data from external weather APIs
- **Asynchronous Programming** – Handle async operations with promises/async-await
- **Error Handling** – Gracefully handle network failures and API errors
- **Geolocation API** – Access user's geographic location
- **Data Parsing** – Process and format API response data
- **Loading States** – Provide feedback during data fetching
- **Conditional Rendering** – Show different UI based on data availability
- **Unit Conversion** – Convert between different temperature units


## Technical Concepts Covered

- REST API integration
- JSON data handling
- Async/await JavaScript
- Fetch API or Axios
- Geolocation API
- Error handling patterns
- Loading state management
- Responsive design
- CSS animations and transitions


## Project Structure

```
weather-app/
├── index.html          # Main HTML structure
├── styles.css          # Styling and responsive design
├── script.js           # API integration and app logic
└── README.md           # Project documentation
```


## Getting Started

1. Sign up for a free weather API key (OpenWeatherMap, WeatherAPI, etc.)
2. Create the basic HTML structure with search and display areas
3. Style the weather interface with modern CSS
4. Implement API integration for fetching weather data
5. Add search functionality and error handling
6. Include geolocation support
7. Add temperature unit conversion
8. Implement bonus features as you progress


## API Setup

You'll need a weather API key. Popular free options:
- **OpenWeatherMap** – 1000 calls/day free tier
- **WeatherAPI** – 1 million calls/month free tier
- **AccuWeather** – 50 calls/day free tier

Store your API key securely and don't commit it to version control.


## Implementation Tips

- Use environment variables or config files for API keys
- Implement proper error handling for network failures
- Cache API responses to reduce calls and improve performance
- Use appropriate loading states for better UX
- Handle edge cases like invalid city names gracefully
- Consider using a weather icon library for consistent visuals


## Next Steps

After completing this project, you'll be ready for:
- More complex API integrations
- Building data-driven applications
- Working with real-time data streams
- Creating dashboard applications
- Implementing authentication and user accounts
