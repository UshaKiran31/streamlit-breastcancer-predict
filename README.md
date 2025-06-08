# Breast Cancer Diagnosis Predictor

## Overview

The Breast Cancer Diagnosis app is a machine learning-powered tool designed to assist medical professionals in diagnosing breast cancer. Using a set of measurements, the app predicts whether a breast mass is benign or malignant. It provides a visual representation of the input data using a radar chart and displays the predicted diagnosis and probability of being benign or malignant. The app can be used by manually inputting the measurements or by connecting it to a cytology lab to obtain the data directly from a machine. The connection to the laboratory machine is not a part of the app itself..

The app was developed as a machine learning exercice from the public dataset [Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)). Note that this dataset may not be reliable as this project was developed for educational purposes in the field of machine learning only and not for professional use.

### 🚀 Live Demo

You can access the live version of my application on [Streamlit Community Cloud](https://app-breastcancer-predict.streamlit.app/).

---

## Features

- ✅ Predicts whether a breast tumor is benign or malignant
- 📊 Radar chart visualization of input features
- 🔢 Manual input or potential lab data integration (not implemented)

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Streamlit
- Plotly (for radar charts)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/UshaKiran31/streamlit-breastcancer-predict.git
   cd streamlit-breastcancer-predict
2. Install dependencies::
   ```bash
   pip install -r requirements.txt
3. Run the app:
   ```bash
   streamlit run app.py
