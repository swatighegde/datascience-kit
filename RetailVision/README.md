# RetailVision – U.S. Retail Sales Forecasting

## 📌 Overview
This project focuses on forecasting **U.S. monthly retail sales** using historical data from the Federal Reserve Bank of St. Louis (FRED).  To identify long-term trends and seasonal effects, multiple time series forecasting techniques—including  **Linear Regression, SARIMA, and Prophet** are applied to improve forecast accuracy for business decision-making.

---

## 🎯 Objectives  
- Perform **time series forecasting** on U.S. retail sales data (1992–2025).  
- Explore **seasonality and anomalies** in the dataset.  
- Compare **different forecasting models** (Linear Regression, SARIMA, Prophet).  
- Provide forecasts to support **strategic planning in inventory and marketing**.  

---

## 📂 Project Structure  
RetailVision/
├── data/
│ └── us_advance_retail_sales.csv
│
├── notebooks/
│ └── us_retail_sales_forecasting_analysis.ipynb
│
├── README.md

---

## 🛠️ Tech Stack  
- **Language:** Python 
- **Libraries:**  
  - `pandas`, `numpy` → data manipulation  
  - `matplotlib`, `seaborn` → visualization  
  - `scikit-learn` → preprocessing, evaluation  
  - `linear_model` → LinearRegression
  - `statsmodels`  → SARIMA model 
  - `prophet`      → Prophet Model
  - **Environment:** Jupyter Notebook  

--- 

## 📊 Dataset 
- **Source:** [FRED Economic Data – Advance Retail Sales: Retail Trade (RSXFS)](https://fred.stlouisfed.org/series/RSXFS)

---

## 📈 Results  

- **Linear Regression with lag features** performed best among the models, delivering the lowest error rates with MAE as **3443** and RMSE as **4101**
- **The SARIMA model**, despite being designed for time series with seasonality, performed worse than the simple Linear Regression model, with higher **MAE(4,309)** and **RMSE(5,225)** values.
- **The Prophet model** had the highest **MAE (8,333)** and **RMSE (9,647)**, making it the least accurate of the three. 

---

## 🚀 How to Run  

```bash
# Clone repository
git clone https://github.com/swatighegde/datascience-kit.git
cd RetailVision

# Launch notebook
jupyter notebook us_retail_sales_forecasting_analysis.ipynb