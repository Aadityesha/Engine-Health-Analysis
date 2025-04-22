# Engine Health Monitoring with Feature Engineering

This project explores predictive maintenance and engine health analysis using sensor data. The objective is to engineer relevant features from raw telemetry to detect anomalies or infer engine performance states more effectively.

## 📌 Project Highlights

- **Focus**: Engine health prediction using sensor readings such as temperature, pressure, and fuel data.
- **Tech Stack**: Python, Pandas, Matplotlib, Seaborn, Scikit-learn.
- **Goal**: Use exploratory data analysis (EDA) and custom feature engineering to uncover patterns that may indicate equipment wear or failure.

## 🧠 Feature Engineering

The notebook explores and creates meaningful features such as:

- **Temperature Difference**: Difference between `Lub oil temp` and `Coolant temp` to highlight thermal stress.
- **Pressure Ratios**: Ratios like `Lub oil pressure` to `Fuel pressure` or `Coolant pressure` to examine internal relationships.
- Additional transformations to reveal hidden signals within the raw data.

## 📊 Exploratory Data Analysis

- Visualization of sensor distributions and correlations.
- Detection of trends and outliers that may indicate early signs of engine issues.

## 🚀 Getting Started

1. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the notebook:
   ```bash
   jupyter notebook Engine_Health.ipynb
   ```

## 🛠️ Requirements

- Python 3.7+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, scikit-learn

