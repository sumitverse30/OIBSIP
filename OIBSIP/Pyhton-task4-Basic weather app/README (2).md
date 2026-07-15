
# Project Title

A brief description of what this project does and who it's for

Build a Python application that fetches and displays real-time weather data for a user-specified location using a weather API. Beginners build a command-line tool; advanced builds a graphical app with forecasts and visual elements.
Tech Stack — Beginner: Python, requests, json, OpenWeatherMap API (free tier) Tech Stack — Advanced: Python, requests, tkinter or PyQt5, PIL/Pillow for icons, OpenWeatherMap API
Feature Checklist — Beginner Tier:
[ ] Prompt user to enter a city name or ZIP code
[ ] Make an API call to OpenWeatherMap (or equivalent free API) and parse the JSON response
[ ] Display: current temperature (°C and °F), humidity percentage, weather condition description (e.g., "Partly Cloudy"), wind speed
[ ] Handle API errors gracefully: city not found, network timeout, invalid API key
[ ] Input validation: reject empty city input
Feature Checklist — Advanced Tier (includes all Beginner features, plus):
[ ] GUI window with a city input field, a "Get Weather" button, and a results panel
[ ] Display weather icons corresponding to the current condition (use OpenWeatherMap icon URLs)
[ ] Hourly forecast panel: show weather for the next 6 hours
[ ] Daily forecast panel: show weather for the next 5 days
[ ] Unit toggle: Celsius / Fahrenheit switch button
[ ] (Bonus) Automatic location detection using the user's IP address via ipinfo.io API (free tier)
[ ] Error messages shown inside the GUI (not terminal print statements)
Self-Sourcing Guideline: Register for a free API key at openweathermap.org — the free tier allows 60 calls/minute and is sufficient for this project. Search "Python weather app OpenWeatherMap API tutorial" on YouTube. Reference the OpenWeatherMap API documentation for JSON response structure. For the GUI version, search "Python tkinter weather app tutorial".
