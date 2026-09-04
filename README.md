# 🌦️ Weather App

A desktop weather application built with **Python and PyQt5** that fetches current weather information using the **OpenWeatherMap API**.

## ✨ Features
```text
- 🌍 Search weather by city name
- 🌡️ Display current temperature in Celsius
- ☁️ Display weather conditions
- 😊 Weather condition emoji
- ⚠️ Basic error handling for invalid cities or API requests
- 🖥️ Simple PyQt5 graphical user interface
- 🔐 API key stored securely using environment variables
```
## 🛠️ Technologies Used
```text
- Python
- PyQt5
- Requests
- python-dotenv
- OpenWeatherMap API
```
## 📁 Project Structure

```text
weather-app/
│
├── weather API.py
├── .env.example
├── .gitignore
└── README.md
```
## ⚙️ Installation
```text
1. Clone the repository
git clone https://github.com/punit-jangid/weather-app.git
cd weather-app
2. Install dependencies
pip install requests PyQt5 python-dotenv
3. Configure the API key
Create a .env file in the project directory:
OPENWEATHER_API_KEY=your_api_key_here
4. Run the application
python "weather API.py"
```

## 🚀 How It Works
```text
1.Enter a city name in the application.
2.Click the weather button.
3.The application sends a request to the OpenWeatherMap API.
4.The current weather data is retrieved and displayed in the GUI.
```
## 🔐 Security
```text
The API key is loaded from an environment variable instead of being stored directly in the Python source code.
```
## 🎯 Project Goal
```text
This project was built to practice:

Python programming
API integration
GUI development with PyQt5
Environment variables
Error handling
Working with external APIs
```
## 👨‍💻 Author
```text
Punit Jangid

BTech CSE Student | Python Developer | Exploring AI & Backend Development
```