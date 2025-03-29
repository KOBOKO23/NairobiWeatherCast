# 🌦 NairobiWeatherCast

NairobiWeatherCast is a meteorological visualization and forecasting tool designed to help forecasters analyze weather parameters at multiple pressure levels over Nairobi. It enables real-time exploration of key atmospheric variables such as MSLP, winds, temperature, and humidity across pressure levels (surface, 850mb, 700mb, etc.) to support daily forecast preparation.

---

## 🎯 Project Goals

- Enable visual inspection of atmospheric parameters for operational forecasting  
- Show how pressure, wind, RH, and temperature change at different levels  
- Provide real-time and historical plots of parameters every 15 minutes  
- Build a foundation for a custom forecasting model using open-source tools  
- Deliver a forecaster-friendly interface that mimics standard forecasting workflows  

---

## 🛠 Technologies Used

- Python – Core programming language  
- Flask – Backend web framework  
- MySQL – Data storage for parameter metadata and forecast info  
- pandas – Data handling and transformation  
- Plotly / Leaflet.js – Interactive visualizations and mapping  
- xarray, netCDF4, cdsapi – For weather data extraction and manipulation  
- CRON / Scheduler – For fetching data every 15 minutes  

---

## 📁 Project Structure

```
nairobiweathercast/
├── static/
│   ├── scripts/
│   └── images/
├── templates/
│   └── index.html
├── data/
│   ├── raw/
│   ├── processed/           
│   └── sample_forecast.csv
├── app.py                   
├── fetch_data.py          
├── model.py                 
├── utils.py                
├── console.py             
├── requirements.txt
└── README.md
```

---

## 🚀 Getting Started

1. Clone the repository:
   ```
   git clone https://github.com/your-username/nairobiweathercast.git
   cd nairobiweathercast
   ```

2. Create and activate a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate       # On Unix/macOS
   venv\Scripts\activate          # On Windows
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the Flask app:
   ```
   python app.py
   ```

5. Access the dashboard:
   ```
   http://127.0.0.1:5000/
   ```

---

## 📊 Key Features

- Visual exploration of MSLP, temperature, wind, RH at pressure levels  
- Interactive navigation through time (past and forecast hours)  
- Real-time data fetching (every 15 minutes)  
- Forecast support for daily decisions  
- Expandable for future ML-based model integration  

---

## 📌 Forecast Workflow

1. Select a weather parameter (e.g., 850mb Winds, MSLP)  
2. Choose pressure level  
3. View visual plot of behavior across time  
4. Combine info from different levels to make a conclusive forecast  

---

## 🌱 Future Plans

- Add rainfall prediction using ML/AI model  
- Incorporate real-time satellite and radar overlays  
- Enable user accounts for forecast generation and history  
- Mobile-friendly and multi-location support  
- Build REST API for programmatic access  

---

## 👨‍💻 Author

Philip Koboko  
Meteorology Student & Developer  
Created as part of an Operational Meteorology Training Course (2025)

---

