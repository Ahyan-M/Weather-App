# Weather App

This is a simple weather app built with PyQt5 and OpenWeatherMap API. The app allows you to enter a city name and get real-time weather information, including temperature, description, and an emoji representing the current weather.

## Features

- Get real-time weather data from OpenWeatherMap API.
- Displays temperature, weather description, and an emoji representing the current weather.
- Beautiful graphical interface using PyQt5.

## Requirements

Before running the app, make sure you have the following installed:

- Python 3.x
- PyQt5
- requests
- OpenWeatherMap API key (free account)

## Installation

### Step 1: Install the Required Libraries

To run the app, you need to install the required Python libraries. Open your terminal or command prompt and run the following command:

```bash
pip install pyqt5 requests
```
Step 2: Get Your OpenWeatherMap API Key
Go to the OpenWeatherMap website.
Sign up for a free account.
Once signed in, navigate to the API section and generate an API key.
Copy the API key to your clipboard.

Step 3: Update the API Key in the Code
Now that you have your API key, you need to update the code to use your key.

Open the weather_app.py file.

Find the following line of code: api_key = 

api_key = "YOUR_API_KEY"  # Replace with your actual API key
Replace "YOUR_API_KEY" with your actual API key (the one you copied from OpenWeatherMap).

Step 4: Running the App
Once you've updated the API key in the code, you can run the app by executing the following command in your terminal or command prompt:

python weather_app.py
This will open a graphical window where you can enter a city name, click the "Get Weather" button, and see the weather details, including temperature, description, and an emoji representing the current weather.

