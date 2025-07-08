# 🥟 Dumpling Location Intelligence

**An end-to-end data project to identify the best locations to open a dumpling restaurant in Mumbai using open-source geospatial APIs and scoring metrics like foot traffic and competition.**

---

## 🚀 Project Overview

This project uses open-source location data and Python libraries to help food entrepreneurs identify optimal areas for opening a dumpling-focused restaurant in South Mumbai

### 📍 Goals:
- Analyze foot traffic based on proximity to offices, schools, and hospitals.
- Detect nearby restaurants that could act as competitors.
- Evaluate local spending habits — food delivery, restaurant spend, and average income (via open datasets or proxies).
- Understand customer demographics — working professionals, students, families.
- Score areas based on opportunity vs. saturation.
- Visualize top-scoring zones on an interactive map.
- Reverse geocode coordinates to actual locality names.


## 🛠️ Tech Stack

- **Python 3.11**
- 📦 `fastai`, `geopandas`, `folium`, `geopy`, `requests`, `shapely`
- 🌍 `OpenStreetMap` & `Overpass API` for geodata
- 🧠 Data analysis + scoring using basic logic (no heavy ML)

---

## 📂 Folder Structure

```bash
dumpling-location-intelligence/
│
├── data/                     # Processed CSVs and geodata
├── notebooks/
│   ├── dumpling_analysis.ipynb         # Main all-in-one notebook
│
├── README.md
