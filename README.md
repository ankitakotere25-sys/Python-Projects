# PM2.5 Prediction using Machine Learning

##  Project Overview

This project focuses on predicting **PM2.5 air pollution levels** using Machine Learning techniques. PM2.5 refers to fine particulate matter with a diameter of 2.5 micrometers or less, which can be harmful to human health.

The goal of this project is to build a predictive model that estimates PM2.5 levels based on environmental and pollutant data.

---

##  Objectives

* Analyze air quality data
* Understand relationships between pollutants and PM2.5
* Build and evaluate regression models
* Deploy the model using Streamlit (optional)

---

##  Dataset Features

The dataset includes the following features:

* PM10
* NO2 (Nitrogen Dioxide)
* SO2 (Sulfur Dioxide)
* CO (Carbon Monoxide)
* O3 (Ozone)
* Temperature
* Humidity
* Wind Speed

**Target Variable:**

* PM2.5

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Streamlit (for deployment)

---

##  Exploratory Data Analysis (EDA)

* Checked missing values and handled them
* Visualized feature distributions
* Correlation analysis between variables
* Identified key factors affecting PM2.5

---

##  Model Building

The following models were used:

* Linear Regression
* Random Forest Regressor
* Support Vector Regression (SVR)

---

##  Model Evaluation Metrics

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

---

##  Results

* Random Forest performed best among all models
* Achieved higher accuracy compared to linear models
* Identified PM10, NO2, and CO as major contributing factors

---

##  Streamlit App

A web application was built using Streamlit to:

* Input environmental parameters
* Predict PM2.5 levels in real-time

---

##  Project Structure

```
├── data/
├── notebooks/
├── model/
├── app.py
├── requirements.txt
└── README.md
```



##  Conclusion

This project demonstrates how machine learning can be applied to environmental data to predict air pollution levels and support better decision-making.

