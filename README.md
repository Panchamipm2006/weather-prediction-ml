# 🌤️ Weather Intelligence & Temperature Prediction Dashboard

A responsive, zero-latency weather dashboard and real-time Machine Learning prediction engine hosted directly on GitHub Pages. This application fetches live global meteorological data via Open-Meteo REST APIs and computes daily temperature forecasts alongside statistical/ML baseline model predictions.

🚀 **[View Live Interactive Dashboard](https://panchamipm2006.github.io/weather-prediction-ml/)**

---

## 📌 Project Overview

Traditional Machine Learning web applications often suffer from slow server spin-up times (cold starts) when hosted on free-tier backend platforms. This project addresses that issue by deploying a client-side execution model that runs dynamically in the browser via GitHub Pages, delivering instant user feedback with **0ms backend latency**.

### Key Features
* 🔍 **Global City Geocoding**: Search real-time weather data for any city worldwide.
* ⚡ **Live Meteorological Metrics**: Instant display of temperature, humidity, wind speed, and atmospheric pressure.
* 📈 **Interactive 7-Day Graph**: Visualization of Max Temp, Min Temp, and ML Predicted Mean built with Chart.js.
* 📊 **Structured Metrics Table**: Comprehensive 7-day tabular breakdown showing daily trend metrics.
* 🤖 **Client-Side Prediction Engine**: Dynamic execution of feature-weighted temperature estimation logic based on atmospheric features.

---

## 🛠️ Tech Stack & Architecture

* **Frontend**: HTML5, CSS3 (Modern Glassmorphism Design), Vanilla JavaScript (ES6+)
* **Data Visualization**: Chart.js
* **Data Source**: Open-Meteo Geocoding & Weather Forecast APIs
* **Machine Learning / Analysis**: Python, Jupyter Notebook, Scikit-Learn, Random Forest Regression (Model Training & EDA)
* **Deployment**: GitHub Pages (Static Edge Hosting)

---

## 📁 Repository Structure

```text
├── index.html                                 # Live Web Application Dashboard
├── Weather_Intelligence_ML_Prediction...ipynb  # EDA, Feature Engineering & ML Training Notebook
├── weather_random_forest_model.pkl            # Serialized Random Forest Model
├── weather_model_features.pkl                 # Feature Scaling/Encoding Metrics
├── app.py                                     # Python Server Endpoint Code (Gradio/Flask)
└── requirements.txt                           # Python Dependencies
