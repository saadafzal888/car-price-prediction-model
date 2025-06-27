# Car Price Prediction Model

A data science project that predicts used car prices using machine learning. This repo includes end-to-end steps: data exploration, preprocessing, model training, evaluation, and visualizations. Built with Python, Pandas, Scikit-learn, and Matplotlib/Seaborn.

---


---

## Exploratory Data Analysis (EDA)

Here are some of the key insights from the EDA:

### 🔹 Distribution of Raw Prices
![price_distribution_raw](images/price_distribution_raw.png)

### 🔹 Distribution of Log Prices
![log_price_distribution](images/log_price_distribution.png)

### 🔹 Price vs Fuel Type
![fuel_type_vs_price_boxplot](images/fuel_type_vs_price_boxplot.png)

### 🔹 Price vs Transmission Type
![transmission_type_vs_price_boxplot](images/transmission_type_vs_price_boxplot.png)

### 🔹 Price vs Owner Type
![owner_type_vs_price_boxplot](images/owner_type_vs_price_boxplot.png)

### 🔹 Price vs Seller Type
![seller_type_vs_price_boxplot](images/seller_type_vs_price_boxplot.png)

### 🔹 Price vs Car Make
![make_vs_price_boxplot](images/make_vs_price_boxplot.png)

### 🔹 Price vs Color
![color_vs_price_boxplot](images/color_vs_price_boxplot.png)

---

## Model & Pipeline

- Features encoded using One-Hot Encoding
- Log transformation applied on skewed price
- Regression models tried: **Linear Regression, Ridge, Lasso, Random Forest**
- Final model evaluated using **R² score** and **residual analysis**

### 🔸 Pipeline Architecture
![pipeline_architecture](images/pipeline_architecture.png)

### 🔸 Residuals of Final Model
![residuals_training_data](images/residuals_training_data.png)

---

## 📈 Results

- Best model achieved high performance on test set
- Log-transformed prices allowed better residual behavior
- The final model generalizes well and handles categorical features efficiently

---

## 🛠️ Tech Stack

- **Python** 3.x
- **Pandas**, **NumPy**
- **Scikit-learn**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

---


