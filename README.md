# 🌱 EcoWatt

### Sustainable Solutions: For Every Home, Every Business, Every Planet!

**EcoWatt** is a web-based renewable energy platform built with **Python and Django** to help users explore sustainable energy solutions and understand their potential energy and cost benefits.

The platform combines **energy calculations, renewable energy data, interactive maps, weather information, and clean-energy resources** into a single web application.

---

## ✨ Features

### ⚡ Energy Calculator

Estimate energy-related costs based on user inputs and regional electricity prices.

The calculator uses state-specific energy pricing data to provide more relevant estimates for users in India.

### ☀️ Solar & 🌬️ Wind Analysis

Explore renewable energy potential using environmental information such as:

- Solar irradiation
- Wind speed
- Geographic location
- Regional energy information

This helps users understand which renewable energy options may be suitable for a particular location.

### 🗺️ Interactive Renewable Energy Map

EcoWatt provides an interactive map using **Leaflet.js**.

Users can explore locations and view renewable-energy-related information geographically.

The map integrates external data sources to provide information such as:

- Location
- Wind conditions
- Solar irradiation
- Renewable energy potential

### 📰 Renewable Energy News

A dedicated news section provides users with information and updates related to:

- Renewable energy
- Solar power
- Wind energy
- Sustainability
- Clean technology

### 📍 Solar Provider Discovery

Users can discover nearby solar-related service providers through location-based search.

The feature uses external location/place data to help users find relevant renewable energy services.

### 🌱 Sustainability Focus

The platform is designed to make renewable energy information more accessible to everyday users and encourage informed decisions about sustainable energy solutions.

---

## 🏗️ Application Architecture

```text
                         EcoWatt
                            │
                            ▼
                    Django Web Application
                            │
          ┌─────────────────┼─────────────────┐
          │                 │                 │
          ▼                 ▼                 ▼
    Energy Calculator   Interactive Map    News Section
          │                 │                 │
          ▼                 ▼                 ▼
    Energy Pricing     Weather / Solar      News API
       Data                Data
          │                 │
          └─────────────────┼─────────────────┐
                            ▼                 │
                     Renewable Energy        │
                        Insights             │
                            │                 │
                            ▼                 ▼
                     User Information & Recommendations
````

---

## 🛠️ Tech Stack

### Backend

* **Python**
* **Django**

### Frontend

* **HTML5**
* **CSS3**
* **JavaScript**
* **Bootstrap**

### Maps & Visualization

* **Leaflet.js**
* Interactive geographic maps

### APIs & External Services

* **OpenWeatherMap API**
* **NewsAPI**
* **Google Places / location services**

### Data Processing

* **Python**
* **JSON**
* Regional energy pricing data

### Deployment

* **Render**

---

## ⚡ How EcoWatt Works

```text
              User
                │
                ▼
        Selects Location / Inputs
                │
        ┌───────┴────────┐
        ▼                ▼
 Energy Calculator   Renewable Map
        │                │
        ▼                ▼
 Regional Prices    Weather / Solar
        │                │
        └───────┬────────┘
                ▼
       Renewable Energy Insights
                │
                ▼
        Make Informed Decisions
```

---

## 📁 Project Structure

```text
EcoWatt/
│
├── manage.py
│
├── <django_project>/
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── ...
│
├── <app>/
│   ├── views.py
│   ├── urls.py
│   ├── models.py
│   └── ...
│
├── templates/
│   ├── ...
│   └── ...
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── requirements.txt
├── manage.py
└── README.md
```

> The exact structure may vary depending on the current version of the project.

---

## 🚀 Installation & Setup

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd EcoWatt
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

#### Windows

```bash
venv\Scripts\activate
```

#### macOS / Linux

```bash
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure API Keys

EcoWatt uses external APIs for some features.

Add the required API keys to the appropriate configuration/environment settings before running the application.

Depending on the current implementation, these may include:

```text
OPENWEATHER_API_KEY
NEWS_API_KEY
GOOGLE_PLACES_API_KEY
```

> Never commit private API keys or secrets to GitHub.

### 5. Apply migrations

```bash
python manage.py migrate
```

### 6. Start the development server

```bash
python manage.py runserver
```

### 7. Open the application

Visit:

```text
http://127.0.0.1:8000/
```

---

## 🌍 Main Modules

### Energy Calculator

Uses user-provided energy consumption information and regional electricity prices to estimate energy costs.

### Renewable Energy Map

Uses Leaflet.js to display location-based renewable energy information through an interactive map.

### Weather Integration

Weather information such as wind conditions can be retrieved from external weather services and incorporated into renewable-energy analysis.

### News Module

Fetches renewable-energy-related news and presents it through the EcoWatt interface.

### Solar Provider Search

Uses location-based services to help users find solar-energy providers and related businesses.

---

## 🎯 Project Objective

The objective of EcoWatt is to create a single platform where users can:

* Understand their energy consumption
* Estimate electricity costs
* Explore renewable energy potential
* Discover solar and renewable-energy providers
* Stay updated with clean-energy developments
* Make more informed sustainability decisions

The project demonstrates how **web development, APIs, geographic visualization, and data-driven calculations** can be combined to address a real-world sustainability problem.

---

## 🔮 Future Scope

EcoWatt can be expanded with more advanced features such as:

* 🤖 AI-based renewable energy recommendations
* ☀️ Personalized solar panel sizing
* 💰 Solar installation cost and ROI calculator
* 📊 Historical energy-consumption analysis
* 🌦️ Solar production prediction using weather data
* 🏠 Home energy-efficiency recommendations
* 🔋 Battery storage recommendations
* ⚡ EV charging cost estimation
* 📈 Renewable energy dashboards
* 📱 Mobile application
* ☁️ Cloud-based user accounts and data storage
* 🧠 Machine-learning-based energy forecasting

---

## 📌 Project Status

✅ **Completed — Academic / Hackathon Project**

EcoWatt was developed as a renewable-energy-focused web application combining multiple technologies and external APIs into a unified platform.

---

## 👨‍💻 Author

**Gagandeep Singh**

B.Tech CSE — AI & Machine Learning

---

⭐ If you found EcoWatt useful or interesting, consider giving the repository a star!
