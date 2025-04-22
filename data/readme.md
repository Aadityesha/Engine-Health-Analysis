
# 📁 Dataset Overview

This folder contains the dataset used for the **Engine Health Monitoring** project. The dataset includes key engine performance metrics collected from various sensors installed in vehicles.

---

## 📊 Features Included

- `Engine RPM`: Rotational speed of the engine.
- `Lub oil pressure`: Pressure of lubricating oil.
- `Fuel pressure`: Fuel line pressure.
- `Coolant pressure`: Coolant system pressure.
- `Lub oil temp`: Temperature of lubricating oil.
- `Coolant temp`: Coolant temperature.
- `Engine Condition`: A target/label column that may represent the engine's operational state.

---

## 🧠 Potential Use Cases

- **Predictive Maintenance**: Train ML models (e.g., regression, decision trees, neural networks) to predict when an engine might require servicing, helping prevent breakdowns.
- **Comparative Engine Analysis**: Compare performance across vehicle types, manufacturers, or maintenance strategies.
- **Fleet Monitoring**: Integrate with real-time telemetry for live monitoring and alert generation.

---

## 🔍 Data Preparation Guidelines

Before training:
- **Preprocessing** may be required (missing value handling, normalization, encoding).
- **Train/Test Split** to evaluate model performance.
- Real-time application could involve integrating the trained model into an onboard diagnostic system or cloud-based engine monitoring platform.

---

## 📁 File Information

- **File Name**: `engine_data.csv`
- **Size**: ~1.3 MB
- **Columns**: 7
- **Update Frequency**: Never
- **License**: CC0: Public Domain
- **Usability Rating**: 8.82/10

---

## 🏷 Tags

`Automobiles`, `Vehicles`, `Machine Learning`, `Sensor Data`, `Predictive Maintenance`, `Engine Diagnostics`

---

## ℹ️ Notes

This dataset was designed to facilitate experimentation with supervised learning techniques. You can use it to practice classification, regression, EDA, and real-world deployment patterns in automotive analytics.

