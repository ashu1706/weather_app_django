# Weather App Django 
Welcome to the Weather App, a Django-based web application that allows users to check the current weather conditions of any city worldwide. This application fetches real-time weather data using a reliable weather API and presents it in a user-friendly interface.

# Features

🌦 Real-time Weather Updates: Get current temperature, humidity, wind speed, and weather conditions for any city.

🌎 Global Coverage: Search for weather information for cities worldwide.

📊 Data Presentation: Clean and intuitive UI to display weather data.

🛠 Built with Django: Powered by Python and Django for efficient backend processing.


![](https://github.com/ashu1706/weather_app_django/blob/main/Screenshot%202024-12-24%20204811.png)

# Tech Stack

1. Backend: Django (Python)

2. Frontend: HTML, CSS, Bootstrap (for responsive design)

3. API Integration: OpenWeatherMap API (or any weather API used)

4. Database: SQLite (default Django database)

# Getting Started

**Prerequisites**

-> Python (>= 3.7)

-> Django (>= 4.0)

-> An API key from OpenWeatherMap

# Installation

1. Clone the repository:
```bash
git clone https://github.com/ashu1706/weather_app_django.git
cd weather_app_django
```

2. Set up a virtual environment:
```bash
python -m venv venv
source venv/bin/activate   # For Windows: venv\Scripts\activate
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

4. Add your API key:
```bash
Create a .env file in the project root.
```

Add the following line:

WEATHER_API_KEY=your_api_key_here

Replace your_api_key_here with the actual API key from OpenWeatherMap.

5. Run migrations:
```bash
python manage.py migrate
```

6. Start the development server:
```bash
python manage.py runserver
```

7. Open your browser and visit
```bash
http://127.0.0.1:8000
```

# How to Use

Enter the name of a city in the search bar.

Click the "Search" button.

View the weather details for the specified city.


