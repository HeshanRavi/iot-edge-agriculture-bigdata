# iot-edge-agriculture-bigdata
Research project on big data analytics and filtering mechanisms at the IoT edge for improving agricultural systems.

# Research-Project-R25-025
# GitHub Repository - https://github.com/HeshanRavi/iot-edge-agriculture-bigdata.git

# Enhancing Agricultural Sustainability through Big Data Analytics and IoT Edge Technologies

## Overview

This research initiative addresses the challenges in paddy farming by integrating IoT, edge computing, and big data analytics to deliver intelligent agricultural solutions. The system is designed to monitor pests, optimize irrigation, predict fertilizer needs, and forecast harvest yields. By leveraging real-time data and machine learning models, it empowers farmers with timely insights and precise control over resource management.

### Key Objectives:
1. **Insect Identification and Damage Forecasting** – Automate pest detection using image recognition and historical risk modeling.
2. **Smart Irrigation Management** – Predict and schedule water delivery based on real-time soil moisture and weather data.
3. **Fertilizer Demand Prediction** – Use environmental and historical data to calculate optimal fertilizer distribution per region.
4. **Harvest Prediction and Planning** – Analyze seasonal patterns to estimate crop yields and enhance planning strategies.

---

## System Components

### **1. IoT-Based Pest Monitoring and Forecasting System**
**Contributor**: Edirimannage R.H.S  
- **Camera-Based Detection**: Captures real-time images of pests through IoT-enabled field cameras.  
- **Species Recognition**: Uses deep learning to classify harmful insects.  
- **Threat Assessment**: Compares live data with historical damage patterns.  
- **Real-Time Alerts**: Sends notifications to farmers with action plans for eco-friendly pest management.

### **2. Smart Irrigation Automation System**
**Contributor**: Abeysinghe R.S  
- **Soil Moisture Sensing**: Continuously monitors water levels in paddy fields.  
- **Forecast-Driven Scheduling**: Predicts irrigation needs using weather data and crop cycles.  
- **Alert Mechanism**: Triggers SMS/app alerts when irrigation is required.  
- **Optimized Usage**: Minimizes water waste and enhances yield.

### **3. Predictive Fertilizer Management System**
**Contributor**: Gamage K.G.M.K  
- **Demand Forecasting**: Utilizes past usage and yield data to predict seasonal fertilizer needs.  
- **Smart Distribution**: Allocates fertilizer efficiently across regions.  
- **Online Reordering**: Streamlines logistics through integrated digital ordering tools.  
- **Monitoring Dashboard**: Tracks stock, distribution, and application patterns.

### **4. Harvest Forecasting System**
**Contributor**: Dangalla D.A.S.I  
- **Historical Weather Analysis**: Integrates climate trends with yield outcomes.  
- **Prediction Models**: Uses ARIMA and LSTM for accurate forecasting.  
- **District-Level Mapping**: Visualizes yield projections by geographic region.  
- **Decision Support Tools**: Aids farmers and authorities in seasonal planning.

---

## System Architecture

![System Diagram](https://private-user-images.githubusercontent.com/99629541/439256709-23a0087c-5f95-4495-9e7d-b008377971bb.png)

**Workflow Overview:**
1. **IoT Sensors & Cameras**: Capture real-time field data (pests, soil, weather).
2. **Edge Processing**: Initial data filtering and image preprocessing on-device.
3. **Cloud-Based Analytics**: Run ML models for prediction and decision support.
4. **User Interfaces**: Mobile and web dashboards for visualization and alerts.

---

## Dependencies

### Hardware
- **ESP32 Microcontroller**: Edge computation and sensor integration.
- **Camera Module**: Image acquisition for pest detection.
- **Soil Moisture Sensor**: Groundwater level monitoring.
- **LoRa / GSM Modules**: Long-range data transmission.

### Software & Libraries
- **Python**: Core ML and data processing language.
- **TensorFlow / PyTorch**: For deep learning and model training.
- **NumPy / Pandas**: Data manipulation and preprocessing.
- **Scikit-learn**: ML algorithm implementation.
- **Firebase / PostgreSQL**: Real-time and historical data storage.

### Frontend & Dashboards
- **React.js / Flutter**: Cross-platform web/mobile interfaces.
- **Dart**: Flutter backend logic.
- **Chart.js / D3.js**: Data visualization components.

---

## Contributors

| Name                  | Role                                | Student ID      |
|-----------------------|-------------------------------------|-----------------|
| Edirimannage R.H.S    | Pest Monitoring & Project Lead      | IT21346354      |
| Abeysinghe R.S        | Smart Irrigation System             | IT21338298      |
| Gamage K.G.M.K        | Fertilizer Prediction System        | IT21263330      |
| Dangalla D.A.S.I      | Harvest Forecasting Module          | IT21339592      |

**Supervisor**:  - Ms. Shashika Lokuliyana

**Co-Supervisor**:  - Mr. Kavinga Yapa

**External Supervisor**:  - Mr. Pramushka Hiruni
