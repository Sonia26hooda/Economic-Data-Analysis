# Economic_Data_Analysis

This repository contains a Jupyter notebook (**Economic_Data_Analysis.ipynb**) that demonstrates a complete data analysis workflow on key macroeconomic indicators.

---

## 📌 Project Overview
The project analyzes historical trends of:
- **GDP**
- **Unemployment Rate**
- **Inflation**
- **Fed Funds Rate**

It performs **exploratory data analysis (EDA)**, visualizes relationships, and uses a **time series model (ARIMA)** to forecast future GDP values.

---

## 🔑 Key Sections
- **Data Collection**: Uses the `pandas-datareader` library to pull data from the FRED database.  
- **Data Cleaning & Merging**: Combines various datasets into a single, comprehensive DataFrame.  
- **Exploratory Data Analysis (EDA)**: Calculates summary statistics, correlation matrices, and generates time series plots.  
- **Statistical Analysis**: Visualizes data relationships with a heatmap and decomposes the GDP time series.  
- **Predictive Modeling**: Fits and evaluates an ARIMA model to forecast GDP.  

---

## ▶️ How to Run the Notebook

1. **Clone the repository:**

   git clone https://github.com/Sonia26hooda/Economic_Data_Analysis.git

3. **Navigate to the project directory:**

   cd Economic_Data_Analysis


3. **Install the required libraries:**

   pip install -r requirements.txt


4. **Open the notebook:**

   jupyter notebook Economic_Data_Analysis.ipynb


 ## Requirements
The project requires the following Python libraries:

pandas

pandas-datareader

matplotlib

seaborn

statsmodels

scikit-learn

numpy

👉 A requirements.txt file is included in this repository for easy installation.


## 📂 Repository Contents

- **Economic_Data_Analysis.ipynb** – The main Jupyter notebook  
- **Dataset CSV files**:
  - `Gdp rate.csv`  
  - `inflation rate.csv`  
  - `unemployment rate.csv`  
  - `interest rate.csv`  
  - `macro data merged.csv` – combined dataset containing all the above files  
- **README.md** – This file  
- **requirements.txt** – A list of all required Python libraries  
