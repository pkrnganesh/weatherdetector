# Weather Detector App

A Django-based web application that detects weather using data from OpenWeatherMap API.

## Description

The Weather Detector App is a web application built with Django that provides users with current weather information for a given location. It fetches weather data from the OpenWeatherMap API and displays it to the user. To use this repo or application, users need to sign up for an API key on the OpenWeatherMap website and provide it in the `views.py` file.

## Screenshots

[to_showcase its funtionality![we1](https://github.com/pkrnganesh/weatherdetector/assets/144223747/22642730-9952-4f15-8c40-c34acb387e36)
![we2](https://github.com/pkrnganesh/weatherdetector/assets/144223747/4efdb52b-70cc-434f-83a2-3886de701467)
]

## Installation

1. Clone the repository:

```bash
git clone https://github.com/myusername/weather-detector-app.git

2. Install dependencies:

pip install -r requirements.txt

3. Set up your OpenWeatherMap API key:

   - Sign up for an API key at [OpenWeatherMap](https://openweathermap.org/).
   - Copy your API key.

   ```python
   # Open views.py file in the project directory.
   # Find the API call to OpenWeatherMap and replace 'YOUR_API_KEY' with your actual API key:

   api_key = 'YOUR_API_KEY'

## Usage

1. Run the Django development server:

   ```bash
   python manage.py runserver
