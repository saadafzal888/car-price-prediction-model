# Car Price Prediction Model

A data science project that predicts used car prices using machine learning. This repo includes end-to-end steps: data exploration, preprocessing, model training, evaluation, and visualizations. Built with Python, Pandas, Scikit-learn, and Matplotlib/Seaborn.

---


---

## Exploratory Data Analysis (EDA)

Here are some of the key insights from the EDA:

### Distribution of Raw Prices  
<img src="images/price_distribution_raw.png" alt="Distribution of Raw Prices" width="400"/>

### Distribution of Log Prices  
<img src="images/log_price_distribution.png" alt="Distribution of Log Prices" width="400"/>

### Price vs Fuel Type  
<img src="images/fuel_type_vs_price_boxplot.png" alt="Price vs Fuel Type" width="400"/>

###  Price vs Transmission Type  
<img src="images/transmission_type_vs_price_boxplot.png" alt="Price vs Transmission Type" width="400"/>

### Price vs Owner Type  
<img src="images/owner_type_vs_price_boxplot.png" alt="Price vs Owner Type" width="400"/>

### Price vs Seller Type  
<img src="images/seller_type_vs_price_boxplot.png" alt="Price vs Seller Type" width="400"/>

### Price vs Car Make  
<img src="images/make_vs_price_boxplot.png" alt="Price vs Car Make" width="400"/>

### Price vs Color  
<img src="images/color_vs_price_boxplot.png" alt="Price vs Color" width="400"/>

---

## Model & Pipeline

- Features encoded using One-Hot Encoding
- Log transformation applied on skewed price
- Regression models tried: **Linear Regression, Ridge, Lasso, Random Forest**
- Final model evaluated using **R² score** and **residual analysis**

### Pipeline Architecture  
<img src="images/pipeline_architecture.png" alt="Pipeline Architecture" width="500"/>

### Residuals of Final Model  
<img src="images/residuals_training_data.png" alt="Residuals of Final Model" width="500"/>


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


