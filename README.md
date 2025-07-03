# 🦠 COVID-19 Death Prediction – SHAASTRA AIML Challenge

> A machine learning solution to forecast COVID-19 death rates across Indian states, developed for the SHAASTRA AIML Hackathon.

---

### 📌 Overview

This project tackles the challenge of predicting COVID-19 death counts using real-world data from January 2020 to August 2021 across Indian states and union territories. Leveraging advanced regression models, we developed a robust pipeline capable of producing accurate and scalable predictions. The final model aids in healthcare resource planning and policy-making.

---

### 👥 Team: Dynamic Trios

* **S Jaiganesh**
* **Aswinth T**
* **GowriSankar P**

---

### 🌟 Problem Statement

The task was to develop a machine learning model that accurately predicts the **number of deaths** from COVID-19 using a dataset consisting of:

* Confirmed Cases
* Cured Cases
* State/Region Information
* Dates

---

### 📊 Exploratory Data Analysis

Key visualizations and insights:

* **State-wise case distribution** helped identify hotspots and severity levels.
* **Time-series plots** uncovered temporal trends in confirmed and recovered cases.
* **Correlation matrix** showed which features most strongly influenced death rates, guiding feature selection.

---

### 🧪 Model Experiments

We evaluated multiple algorithms:

| Model             | Notes                                                   |
| ----------------- | ------------------------------------------------------- |
| Linear Regression | Used as a baseline model                                |
| Random Forest     | Improved accuracy and handled non-linearity             |
| XGBoost           | Excellent with tabular data and feature importance      |
| **LightGBM** ✅    | Final choice for its speed, performance, and robustness |

---

### 🧠 Final Model: LightGBM

**Why LightGBM?**

* High accuracy with low latency
* Handles large datasets well
* Efficient memory usage
* Performs better on imbalanced data

**Performance Metric:**

* **Mean Absolute Error (MAE)** – selected for its interpretability in real-world units (deaths)

---

### 📁 Dataset

* `train_data_covid.csv`: Training data with death labels
* `test_data_covid.csv`: Test data to predict on
* Label encoding was applied to convert categorical features for model compatibility

---

### 🛠️ Tech Stack

* **Python**
* **LightGBM**
* **Pandas**, **NumPy**
* **Scikit-learn** (for preprocessing)
* **Matplotlib/Seaborn** (for EDA)

---


---

### ✅ Outcome & Conclusion

* Developed a scalable and accurate COVID-19 death prediction model using LightGBM.
* The model helps identify high-risk regions, aiding in **resource allocation** and **crisis planning**.
* Scope for future work includes:

  * Integrating mobility and vaccination data
  * Exploring deep learning models for more temporal granularity

---


### 📣 Acknowledgement

This project was developed as part of **SHAASTRA AIML Challenge** hosted by **IIT Madras**.
