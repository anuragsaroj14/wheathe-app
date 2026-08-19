# 🌤️ Weather App

A responsive and user-friendly **Weather Application** built using **HTML, CSS, JavaScript, and Bootstrap**. The application uses a weather API to fetch and display real-time weather information based on the searched city.

## 🚀 About the Project

This Weather App allows users to search for a city and view its current weather conditions.

The application fetches live weather data from the **OpenWeather API** and dynamically displays the weather information using JavaScript.

## ✨ Features

* 🔍 Search weather by city name
* 🌡️ Display current temperature
* 🌤️ Display current weather condition
* 💧 Display humidity
* 💨 Display wind speed
* 🌡️ Display "feels like" temperature
* ☁️ Display weather icons
* 📱 Responsive design
* ⚡ Real-time weather data
* ❌ Error handling for invalid city names
* 🎨 Clean and modern user interface

## 🛠️ Technologies Used

* **HTML5** – Structure of the application
* **CSS3** – Styling and customization
* **JavaScript** – API integration and dynamic content
* **Bootstrap 5** – Responsive layout and UI components
* **OpenWeather API** – Weather data

## 🔗 Weather API

This project uses the **OpenWeather Current Weather API** to retrieve weather information.

The API provides weather data such as:

* Temperature
* Feels-like temperature
* Humidity
* Atmospheric pressure
* Wind speed
* Weather condition
* Weather icon
* Visibility

OpenWeather supports JSON responses and allows temperature units such as Celsius and Fahrenheit. An API key is required to make requests.

## 🔑 API Configuration

To use this project with your own API key:

1. Create an account on OpenWeather.
2. Generate an API key.
3. Open the JavaScript file.
4. Add your API key to the API configuration.

Example:

```javascript
const API_KEY = "YOUR_API_KEY";
```

Example API request:

```javascript
const API_URL =
    `https://api.openweathermap.org/data/2.5/weather?q=${city}&appid=${API_KEY}&units=metric`;
```

The `units=metric` parameter returns temperature in Celsius.

> **Security Note:** Do not commit a real API key to a public GitHub repository. If the key is exposed, regenerate/revoke it from your API provider and use a safer configuration approach for production.

## 📂 Project Structure

```text
weather-app/
│
├── index.html


## ⚙️ How It Works

```text
User enters city
       ↓
JavaScript gets city name
       ↓
Weather API request
       ↓
API returns JSON weather data
       ↓
JavaScript processes response
       ↓
Weather information displayed on UI
```

## 💻 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/weather-app.git
```

### 2. Open the Project

```bash
cd weather-app
```

### 3. Add Your API Key

Open:

```text
js/script.js
```

and add your OpenWeather API key.

### 4. Run the Application

Open:

```text
index.html
```

in your web browser.

You can also run the project using **VS Code Live Server**.

## 📸 Screenshot

Add your project screenshot here:

```markdown
![Weather App Screenshot](images/weather-app.png)
```

## 🌐 Live Demo

**Live Website:**
YOUR_NETLIFY_URL

## 📚 What I Learned

Through this project, I practiced:

* Working with REST APIs
* Using JavaScript `fetch()`
* Handling JSON responses
* DOM manipulation
* Asynchronous JavaScript
* Error handling
* Responsive web design
* Bootstrap components
* Integrating third-party APIs
* Displaying dynamic data on a webpage

## 🔮 Future Improvements

* 📍 Detect weather using user's location
* 📅 Add multi-day weather forecast
* 🌙 Add dark/light mode
* 🌡️ Add Celsius/Fahrenheit toggle
* 🕐 Add hourly forecast
* 🌧️ Add weather animations
* 📊 Add weather charts

## 👨‍💻 Author

**Anurag**

Java Full Stack Developer

## ⭐ Support

If you like this project, consider giving the repository a ⭐ on GitHub.

---

**Built with ❤️ using HTML, CSS, JavaScript & Bootstrap**
