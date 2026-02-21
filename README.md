# Weather App 🌦️

## Overview

This is a simple Weather Application built using **HTML, CSS, and JavaScript**. The app allows users to search for any city and view real‑time weather information such as temperature, humidity, and wind speed using the OpenWeatherMap API.

---

## Features

* Search weather by city name
* Displays temperature in Celsius
* Shows humidity and wind speed
* Dynamic weather icons (Clouds, Rain, Clear, Mist, Drizzle)
* Error handling for invalid city names
* Responsive card‑style UI

---

## Technologies Used

* HTML5
* CSS3
* JavaScript (Fetch API)
* OpenWeatherMap API

---

## Project Structure

```
Weather-App/
│── index.html
│── style.css
│── script.js
│── images/
│     ├── search.png
│     ├── rain.png
│     ├── clouds.png
│     ├── clear.png
│     ├── drizzle.png
│     ├── mist.png
│     ├── humidity.png
│     └── wind.png
│── Weather-App.zip
│── README.md
```

---

## How to Run the Project (Very Simple)

### Step 1 — Download

* Download the folder or extract the ZIP file
* Make sure all files remain in the same structure (images folder included)

### Step 2 — Open the App

Just double click **index.html**

OR

Right click → Open with → Chrome / Edge / Firefox

That’s it 🎉 No installation required.

---

## API Setup (Important)

This project uses OpenWeatherMap API.

If API stops working, create your own key:

1. Go to [https://openweathermap.org/api](https://openweathermap.org/api)
2. Create a free account
3. Generate API key
4. Open `script.js`
5. Replace the API key:

```javascript
const apiKey = "YOUR_API_KEY_HERE";
```

---

## How It Works

1. User enters city name
2. App sends request to weather API
3. API returns JSON weather data
4. JavaScript updates UI dynamically
5. Weather icon changes based on condition

---

## Possible Improvements

* Add Enter key search support
* Add loading animation
* Add forecast (5‑day weather)
* Add geolocation detection
* Add dark/light mode toggle

---

## Author

Frontend Mini Project – Weather Application
