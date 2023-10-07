# weatherchecker
Weather Data Retrieval using OpenWeatherMap API
Overview
This Python script allows you to retrieve weather data for a specified city using the OpenWeatherMap API. It fetches information such as the current weather conditions (description) and temperature (in Celsius) for the provided city.

Prerequisites
Before using this script, you need to obtain an API key from OpenWeatherMap. You can sign up for a free API key on their website at https://openweathermap.org/api.

Installation
Clone this repository or download the script directly.

Install the required Python library, requests, if you haven't already. You can install it using pip:

Copy code
pip install requests
Usage
Open the script (weather_data.py) in a Python code editor or IDE.

Replace "your api key" in the API_KEY variable with your OpenWeatherMap API key.

Run the script.

You will be prompted to enter the name of the city for which you want to retrieve weather data.

The script will make an API request to OpenWeatherMap, and if successful, it will display the current weather conditions and temperature for the specified city. If there's an error, it will display an error message.

Example
Here's an example of how to use the script:

vbnet
E.G:
  Enter a city name: New York
  Weather: Clouds
  Temperature: 17.15 Celsius
  
License
This script is provided under the MIT License.
