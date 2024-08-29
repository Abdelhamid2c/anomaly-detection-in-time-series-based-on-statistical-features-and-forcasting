# Predictive Maintenance System

## Project Overview
This project focuses on implementing an unsupervised method for anomaly detection in time series data, particularly in vibratory signals. The main goal is to enhance early fault detection in industrial machines by using advanced statistical and machine learning algorithms. The developed system allows for continuous monitoring, improving maintenance planning, reducing operational costs, and preventing unexpected breakdowns.

## Features
- **Anomaly Detection:** Using statistical features to identify abnormal behavior in time series data.
- **Forecasting:** Predicting future values of vibratory signals using an LSTM model.
- **User Interface:** A Streamlit-based web application for visualizing and interacting with the data.

## Prerequisites
- Python 3.8 or later
- Required Python libraries listed in `requirements.txt`

## How to Run

1. **Clone the Repository:**
   ```bash
   git clone <your-repository-url>
   cd <your-repository-folder>
2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
3. **Run the Streamlit Application:**
   ```bash
   streamlit run Streamlit/PdM.py

