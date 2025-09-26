# Eco_Vision_Predictorr
"An LSTM model to forecast deforestation in Rondônia, Brazil using Google Earth Engine data."

***

## 💡 Project Overview

This project provides a robust solution for monitoring and predicting deforestation. It uses historical NDVI (Normalized Difference Vegetation Index) data, extracted from **Landsat-8 satellite images**, to train a specialized time-series model.

The primary goal was to analyze changes in the Rondônia state of Brazil (a deforestation hotspot) and forecast its **NDVI value for the year 2025**.

***

## ⚙️ Methodology & Key Features

The project follows a comprehensive Machine Learning pipeline, showcasing proficiency in geospatial data handling and deep learning:

* **Data Extraction (Google Earth Engine):** Programmatic access and cleaning of historical NDVI data from 2015 to 2024 using the **Google Earth Engine (GEE) Python API**.
* **Data Preprocessing:** Time-series preparation, handling of missing values, and normalization for stable model training.
* **Model Building (LSTM):** Implementation of a **Long Short-Term Memory (LSTM)** neural network, which is uniquely suited for modeling sequential data like NDVI over time.
* **Forecasting:** The trained LSTM model was used to generate a single, projected NDVI value for the target year 2025.

***

## 📈 Final Result

Based on the historical data and the trained LSTM model, the predicted NDVI value for the specified area in Rondônia for 2025 is:

> **Predicted NDVI Value (2025): 0.3383**

This value suggests a continued trend of **forest degradation** compared to previous years, validating the model's ability to capture long-term environmental patterns.

***

## 💻 Technology Stack

* **Programming Language:** Python
* **Deep Learning:** TensorFlow / Keras (for the LSTM model)
* **Data Handling:** Pandas, NumPy
* **Geospatial Tool:** Google Earth Engine (GEE) API
* **Visualization:** Matplotlib

***

## ▶️ Getting Started

### Prerequisites

To run this project, you will need the following Python libraries. They can be installed using the provided `requirements.txt` file.

### Installation

1.  **Clone the Repository:**
    ```bash
    git clone (https://github.com/guptaasakshi/Eco_Vision_Predictorr.git)
    cd Eco_Vision_Predictorr
    ```
2.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3.  **Run the Notebook:**
    Open the main code file (e.g., `LSTM.ipynb`) in a Jupyter environment or Google Colab and execute the cells sequentially.

***

**Project by:** [Sakshi Gupta]
