# 🚗 NYC Accident Analysis (2020)

*A data-driven exploration of traffic accidents in New York City*

## 📌 Overview
This repository analyzes **New York City traffic accidents from 2020** using **Python, Pandas, Matplotlib, Seaborn, and Folium**. The goal is to uncover insights into accident patterns, severity, and high-risk locations.

## 📊 Key Features
✅ **Data Cleaning & Preprocessing**  
✅ **Exploratory Data Analysis (EDA)**  
✅ **Time-Series Analysis** (Accidents by hour, day, borough)  
✅ **Geospatial Analysis** (Heatmaps of accident-prone areas)  
✅ **Accident Severity Analysis** (Injuries vs. fatalities)  

## 📌 Data Source
The dataset (`NYC_Accidents_2020.csv`) contains **74,881 records** with **29 columns**, including:

- **Crash Details**: Date, time, borough, ZIP code  
- **Location Data**: Latitude, longitude  
- **Injuries & Fatalities**: Pedestrians, cyclists, motorists  
- **Contributing Factors**: Driver distraction, speeding, etc.  
- **Vehicle Types**: Vehicle categories involved in accidents  

---

## 📊 Data Analysis & Visualizations

### 🕒 Accidents by Time of Day
- Analysis of accident frequency per **hour of the day**.  
- Categorized into **Morning, Afternoon, Evening, and Late Night**.  
- **Findings**: Peak accident hours are typically **afternoon and evening**.  
---

### 📍 Accident Hotspots in NYC
- Used **Folium** to create an **interactive heatmap**.  
- Identified accident-prone areas based on geospatial data.  
- **Findings**: Certain intersections and boroughs have consistently high accident rates.
- 
---

### 🚦 Accidents by Borough
- Comparison of accident counts across **Manhattan, Brooklyn, Queens, Bronx, and Staten Island**.  
- **Findings**: Brooklyn and the Bronx see the highest number of accidents.  

---

### 🔴 Severity Analysis
- **Total Injuries vs. Fatalities** plotted.  
- Analyzed road users most affected (**pedestrians, cyclists, motorists**).  
- **Findings**: Pedestrians and motorists are at **highest risk**.  

---

## 🔮 Future Improvements
✅ **Predictive Modeling**: Forecast accident-prone areas using ML.  
✅ **Weather & Traffic Integration**: Analyze impact on accidents.  
✅ **Real-time Accident Dashboard**: Interactive visualization with **Streamlit** or **Dash**.  

  
