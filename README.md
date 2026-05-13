# 🌤️ Weather App (Flask + OpenWeather API)

A simple but powerful weather application built with **Flask** that fetches real-time weather data from the OpenWeather API.

👉 Live Demo: https://pythonweather-production.up.railway.app/

No setup needed — just enter a city and get real-time weather results.

---

## ⚙️ Features

- 🔍 Search weather by city name
- 🌡️ Real-time temperature updates
- 🌤️ Weather conditions (cloudy, sunny, etc.)
- 📍 Feels-like temperature
- ❌ Handles invalid city input gracefully
- 🌍 Works online after deployment (Railway)

---

## 🛠️ Tech Stack

- Python 🐍
- Flask 🌶️
- HTML / CSS
- OpenWeather API 🌦️
- Railway (Deployment 🚀)

---

## 🧠 What I Learned

This project taught me more than just coding — it taught me **debugging in real environments**:

- How to build a Flask backend
- How APIs return structured JSON data
- How environment variables work in deployment
- How to deploy using Railway
- How frontend (HTML) can break backend logic if not handled correctly

---

## ⚠️ Challenges I Faced

### 1. Deployment vs Local Differences
At first, the app worked locally but failed online.  
The issue was missing environment variables in Railway.

---

### 2. API Key Problems
Even though my API key was correct, I didn’t properly set it in Railway Variables.

---

### 3. HTML Form Issues 😅
One of the biggest problems was actually my HTML:

- Wrong input `name`
- Empty form submissions
- Missing validation

This caused Flask to receive empty or invalid city values, leading to “City Not Found” errors.

---

### 4. Debugging Real Logs
I learned how to use Railway logs to find real backend issues instead of guessing.

---

## 💡 Key Lesson

 “Sometimes the backend is not broken — the frontend is sending the wrong data.”

 
## 👨‍💻 Author

Treasure Nxazonke

Frontend Developer | Python Learner | Aspiring AI Engineer
