# 🏡 California Real Estate Price Predictor using Machine Learning (Multiple Linear Regression)

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

A Machine Learning project utilizing **Linear Regression** to predict housing prices in California. It features an end-to-end pipeline from data ingestion to a real-time interactive simulator.

---

## 📸 Live Demo
![Real State Recognition California](https://github.com/user-attachments/assets/02b31578-8e7c-410c-b39d-9c4f9a54f5ae)

![Demo GIF](demo.gif)

> **Try it yourself in Google Colab:**
> [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](INSERT_YOUR_COLAB_LINK_HERE)

---

## 🚀 Project Achievements
*Aligned with the technical competencies demonstrated in this project:*

* **Predictive Modeling:** Developed a regression model to estimate property values with high precision, utilizing **Scikit-learn** to analyze features like square footage, income, and location.
* **Data Engineering:** Conducted extensive Exploratory Data Analysis (EDA) and feature scaling using **Pandas** and **NumPy**, identifying key market drivers to improve prediction accuracy.
* **Performance Evaluation:** Optimized model results by evaluating metrics such as **Mean Squared Error (MSE)** and **R-squared** to ensure robust performance across the dataset.

---

## 🧠 Model Logic (Mathematical Context)

The model aims to minimize the **Mean Squared Error (MSE)** between the predicted price ($\hat{y}$) and actual price ($y$):

$$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$$

Where the prediction is calculated as a weighted sum of the inputs (features):

$$\hat{y} = w_0 + w_1(\text{Income}) + w_2(\text{HouseAge}) + ... + w_n(\text{Location})$$

* **$w$ (Weights):** Represent the importance of each feature (learned during training).
* **$w_0$ (Bias):** The base price intercept.

---

## 📊 Data Analysis & Insights

### 1. Identifying Key Market Drivers
Using the model's coefficients, we determined which features drive prices up or down.
<img width="2338" height="1588" alt="image" src="https://github.com/user-attachments/assets/1aecff9c-6c24-459d-be61-8b0aa0c0a06d" />
/>


> **Insight:** The analysis reveals that **Median Income** is the strongest predictor of housing prices in this region.

### 2. Correlation Analysis
We analyzed the relationship between variables to avoid multicollinearity.



<img width="2399" height="1625" alt="image" src="https://github.com/user-attachments/assets/2776807f-ac91-4b89-bdf0-49248a1e29ab" />



---

## 🛠️ Tech Stack
* **Core:** Python 3
* **Machine Learning:** Scikit-Learn (LinearRegression, train_test_split)
* **Data Processing:** Pandas, NumPy (Vectorization & Reshaping)
* **Visualization:** Matplotlib, Seaborn
* **Interactive UI:** ipywidgets

---

## 👨‍💻 Author
**Francisco Rivera**
*Computer Science Student @ Tecnológico de Monterrey*
[LinkedIn](www.linkedin.com/in/franciscoarivera) | [GitHub](https://github.com/francisco-rivera-viveros)
