# 🌾 Gujarat Soil Salinity Intelligence Platform

### AI-Powered Geospatial Monitoring, Forecasting & Decision Support System for Soil Salinity Management

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-Dashboard-red)
![GIS](https://img.shields.io/badge/GIS-Geospatial-orange)
![GeoPandas](https://img.shields.io/badge/GeoPandas-Spatial%20Analytics-green)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-brightgreen)
![XGBoost](https://img.shields.io/badge/XGBoost-Predictive%20Modeling-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![SQLite](https://img.shields.io/badge/SQLite-Database-lightgrey)
![Agriculture](https://img.shields.io/badge/Agriculture-Decision%20Support-success)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

# 📸 Dashboard Preview

![Dashboard](assets/dashboard.png)

---

# 🎥 Project Demonstration

👉 Interactive AI-powered dashboard for monitoring and forecasting soil salinity across Gujarat districts.

![Demo](assets/demo.gif)

---

# 🏗️ System Architecture

![Architecture](assets/architecture.png)

---

# 📌 Project Overview

Soil salinity is one of the most serious land degradation challenges affecting agricultural productivity, groundwater quality, and long-term sustainability in arid and semi-arid regions.

The **Gujarat Soil Salinity Intelligence Platform** is an advanced Geospatial Artificial Intelligence (GeoAI) system designed to monitor, analyze, predict, and visualize soil salinity dynamics across Gujarat.

The platform integrates:

* Geospatial datasets
* Historical climate variables
* Vegetation indicators (NDVI)
* Rainfall records
* Temperature patterns
* Machine Learning models
* Deep Learning forecasting models

to generate a comprehensive **Soil Salinity Prediction Index (SSPI)** and provide district-level salinity intelligence for researchers, planners, and policymakers.

The system combines **GIS, Machine Learning, Deep Learning, Forecasting, and Interactive Web Mapping** into a unified decision-support platform.

---

# 🎯 Project Objectives

* Monitor district-wise soil salinity conditions
* Generate Soil Salinity Prediction Index (SSPI)
* Identify salinity-prone regions
* Analyze historical salinity trends
* Forecast future salinity conditions
* Compare machine learning model performance
* Support agricultural planning and land management
* Provide actionable recommendations for mitigation

---

# 🌍 Study Area

### State: Gujarat, India

Gujarat contains extensive coastal zones, canal command areas, inland dry regions, and groundwater-dependent agricultural districts, making it one of India's most important regions for salinity assessment.

The platform covers:

* Coastal Districts
* Canal Irrigation Zones
* Inland Agricultural Regions
* Hilly Low-Salinity Regions

---

# 📊 Dataset Overview

The project integrates multiple environmental and agricultural datasets.

### Data Sources

* District Boundary Data (GeoPackage)
* Historical Weather Data
* Annual Rainfall Records
* Temperature Data
* NDVI Vegetation Indicators
* Agricultural Land Characteristics
* Soil Salinity Parameters

### Processed Features

* Rainfall Annual
* Rabi Temperature
* NDVI
* District Classification
* Zone Type
* Historical SSPI
* Forecasted SSPI

---

# 🧠 Machine Learning Models Implemented

The platform evaluates multiple predictive approaches.

## 1️⃣ Linear Regression

Used as baseline statistical model.

### Purpose

* Benchmark prediction performance
* Understand feature relationships

---

## 2️⃣ Random Forest

Ensemble learning model for nonlinear soil salinity prediction.

### Advantages

* Handles nonlinear interactions
* Robust against overfitting
* Feature importance analysis

---

## 3️⃣ XGBoost

Gradient boosting model for high-performance forecasting.

### Advantages

* High predictive accuracy
* Efficient handling of complex datasets
* Advanced regularization

---

## 4️⃣ Temporal Fusion Transformer (TFT)

Deep learning model for temporal forecasting.

### Advantages

* Time-series forecasting
* Long-term trend learning
* Multi-variable dependency modeling
* Superior predictive performance

---

# 📈 Model Performance

| Model             | MAE  | RMSE | R² Score |
| ----------------- | ---- | ---- | -------- |
| Linear Regression | 7.81 | 9.01 | 0.745    |
| Random Forest     | 7.26 | 8.45 | 0.776    |
| XGBoost           | 6.65 | 8.53 | 0.771    |
| TFT Transformer   | 4.91 | 7.25 | 0.831    |

### Best Performing Model

🏆 **Temporal Fusion Transformer (TFT)**

* R² Score: 0.831
* MAE: 4.91

---

# 🚀 Key Features

## 🗺️ Interactive GIS Dashboard

* District-wise salinity visualization
* Interactive maps
* Dynamic district selection
* Real-time statistics

---

## 📊 Soil Salinity Prediction Index (SSPI)

Automated classification:

| SSPI Range | Category |
| ---------- | -------- |
| 0 – 24     | Low      |
| 25 – 49    | Moderate |
| 50 – 74    | High     |
| 75+        | Critical |

---

## 🌊 Zone-Based Salinity Analysis

### Coastal Zone

* Seawater intrusion assessment
* Coastal salinity monitoring

### Canal Zone

* Waterlogging effects
* Secondary salinization analysis

### Inland Zone

* Groundwater extraction impacts
* Borewell salinity assessment

### Hilly Zone

* Natural low-salinity monitoring

---

## 🔮 Future Forecasting

The platform predicts future salinity conditions using TFT-based forecasting.

Capabilities include:

* Trend forecasting
* District-level prediction
* Risk assessment
* Long-term monitoring

---

## 🎯 Smart Policy Recommendation Engine

Automatically generates management recommendations based on:

* Salinity severity
* Geographic zone
* Risk classification

Examples include:

* Gypsum application
* Drainage management
* Groundwater regulation
* Salt-tolerant crop adoption
* Coastal protection measures

---

# 📍 Dashboard Modules

### Home Dashboard

* Key Performance Indicators
* Salinity Status
* Forecast Overview

### District Analysis

* Historical Trends
* Forecast Trends
* Salinity Classification

### GIS Mapping

* Interactive Folium Maps
* Current Salinity Layer
* Forecast Salinity Layer

### Model Comparison

* Accuracy Metrics
* Performance Evaluation

### Decision Support

* Zone-specific recommendations
* Risk mitigation guidance

---

# 📈 Results & Achievements

### Project Outputs

✅ District-Level SSPI Calculation

✅ Soil Salinity Forecasting

✅ GIS-Based Visualization

✅ Multi-Model Comparison

✅ Decision Support System

✅ Interactive Web Dashboard

✅ Automated Policy Recommendations

### Key Achievement

Developed a complete GeoAI-driven agricultural intelligence platform capable of forecasting soil salinity with **83.1% predictive accuracy**.

---

# 🔄 System Workflow

```text
Weather Data
        │
        ▼
Environmental Variables
(NDVI, Rainfall, Temperature)
        │
        ▼
Feature Engineering
        │
        ▼
SSPI Calculation
        │
        ▼
Machine Learning Models
        │
        ▼
TFT Forecasting
        │
        ▼
SQLite Database
        │
        ▼
GIS Visualization
        │
        ▼
Streamlit Dashboard
        │
        ▼
Decision Support System
```

---

# 🛠️ Technology Stack

## Programming

* Python

## Data Processing

* Pandas
* NumPy

## Geospatial Analytics

* GeoPandas
* Folium

## Machine Learning

* Scikit-Learn
* XGBoost

## Deep Learning

* PyTorch
* PyTorch Forecasting
* Lightning

## Visualization

* Streamlit
* Matplotlib
* Plotly

## Database

* SQLite

---

# 📂 Project Structure

```text
soil_salinity_project/
│
├── app/
│   └── dashboard.py
│
├── data/
│   └── Processed/
│       ├── Gujarat_districts.gpkg
│       ├── salinity_db.sqlite
│       ├── xgb_model.pkl
│       ├── rf_model.pkl
│       ├── linear_model.pkl
│       └── tft_model.ckpt
│
├── outputs/
│   ├── charts/
│   ├── maps/
│   └── tables/
│
├── scripts/
│   ├── 01_setup_spatial.py
│   ├── 02_weather_download.py
│   ├── 03_data_merge.py
│   ├── 04_sspi_calc.py
│   ├── 05_features_trend.py
│   ├── 06_ml_prep.py
│   ├── 07_linear_regression.py
│   ├── 08_rf_xgb.py
│   ├── 08b_tft.py
│   ├── 09_predict_future.py
│   ├── 10_maps_charts.py
│   ├── 11_store_db.py
│   └── 12_validate.py
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

# ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/202519003/soil_salinity_project.git

cd soil_salinity_project
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Application

```bash
streamlit run app.py
```

---

# 🌱 Applications

This platform can support:

* Precision Agriculture
* Soil Health Monitoring
* Climate Resilience Planning
* Agricultural Decision Support
* Sustainable Land Management
* Salinity Risk Assessment
* Environmental Monitoring
* Government Planning Programs
* Smart Agriculture Systems

---

# 🔮 Future Enhancements

* Satellite-based salinity estimation
* Remote sensing integration
* Real-time weather APIs
* District heatmaps
* Explainable AI (XAI)
* Mobile dashboard
* Cloud deployment
* Multi-state expansion
* Farmer advisory system

---

# 👨‍💻 Author

## Mehul B. Chaudhary

### M.Sc. Agriculture Analytics

GIS | GeoAI | Spatial Analytics | Machine Learning | Remote Sensing | Agricultural Intelligence

🔗 LinkedIn:
https://www.linkedin.com/in/mehulkumar-chaudhary-403516230

🔗 GitHub:
https://github.com/202519003

---

# ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.

Your support helps improve open-source geospatial and agricultural intelligence solutions.
