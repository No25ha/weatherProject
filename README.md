🌤️ Weather App

A simple and user-friendly application that displays the current weather for any city worldwide using WeatherAPI.

The user enters a city name, and the app shows:

Temperature

Weather condition

Wind speed

Humidity

Date & location details

🚀 Live Demo

(Add your GitHub Pages or Netlify link here)

🛠️ Tech Stack

React JS (Create React App)

JavaScript (ES6)

CSS / Bootstrap

WeatherAPI

Fetch API

✨ Features

🔍 Search for weather by city name

🌡️ Display current temperature

🌥️ Weather condition (Sunny, Cloudy, Rainy, etc.)

💨 Shows wind speed & humidity

🔄 Auto refresh on search

⚠️ Error handling (invalid city name)

📦 Installation

To run the project locally:

git clone https://github.com/YourUsername/weatherProject.git
cd weatherProject
npm install
npm start


The app will run at:
http://localhost:3000

🔑 Weather API

This project uses WeatherAPI to fetch weather data.
You can get your API key here:
https://www.weatherapi.com/

Insert your key in the request:

const response = await fetch(
  `https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=${city}`
);

🗂️ Folder Structure
weatherProject/
│── public/
│── src/
│   ├── components/
│   ├── App.js
│   ├── index.js
│   ├── App.css
│   └── ...
│── package.json
│── README.md

📸 Screenshots

(Add screenshots of your app here)

Example:

![Weather App Screenshot](./screenshots/home.png)

🧑‍💻 Author

Noha Ali Ahmed

GitHub: https://github.com/YourUsername

LinkedIn: (Add your LinkedIn link)

🎉 License

This project is open-source and free to use.
