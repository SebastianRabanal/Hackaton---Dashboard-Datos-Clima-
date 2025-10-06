# 🌍 Air Quality Dashboard - NASA TEMPO

**A web-based dashboard designed to protect vulnerable populations from air pollution**, using real-time air quality data, meteorological information, and scientific simulations.

---

## 🚀 Features

- 🌫 **Real-time Air Quality Monitoring:** Tropospheric NO₂, PM2.5, and AQI data from NASA TEMPO  
- 🌦 **Weather Integration:** Temperature, wind speed, and humidity metrics  
- 🧬 **Vulnerability Analysis:** Identification of at-risk groups and risk level assessment  
- 💡 **Personalized Recommendations:** Action guidelines based on pollution levels  
- 📊 **Interactive Visualizations:** Historical trends and 24-hour forecasts  
- 🗺 **Risk Mapping:** Visual representation of high-risk zones  

---

## 🛠 Technologies Used

**Frontend:**  
- HTML5  
- CSS3  
- JavaScript  

**Backend:**  
- FastAPI  
- Python 3.10  

**Data Sources:**  
- [NASA TEMPO API](https://www.nasa.gov/tempo) – Air quality data  
- [OpenAQ API](https://openaq.org) – Additional air quality metrics  
- [Open-Meteo API](https://open-meteo.com) – Weather data  

---

## 📋 Prerequisites

Make sure you have the following installed:

- 🐍 Python **3.10** or **3.11** (recommended)  
- 📦 `pip` (Python package manager)

---

## 🗂 Project Structure

Nasa_Project/
├── main.py
├── requirements.txt
├── .gitignore
├── index.html
├── css/
│ └── styles.css
├── js/
│ └── script.js
├── static/
└── README.md


---

## ⚡ Quick Start

Clone the repository and install the dependencies:

```bash
# Clone the repository
git clone https://github.com/LimitCodev/Nasa_Project.git
cd Nasa_Project

# Install dependencies
python -m pip install -r requirements.txt

# Launch the application
py main.py or python -m uvicorn main:app --reload

# Access the dashboard
# Open http://localhost:8000 in your browser
