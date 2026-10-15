# Poverty and Zakat Distribution Analysis and Forecasting in Malaysia

## 📌 Project Overview

This project analyzes poverty rates and zakat distribution across Malaysian states from **2007 to 2022** using data analytics and machine learning techniques. The objective is to identify historical trends, explore patterns between poverty rates and zakat distribution, and develop predictive models to estimate poverty rates.

The findings may provide useful insights for understanding poverty trends and supporting data-driven planning for social welfare initiatives in Malaysia.

## 🎯 Objectives

- Analyze historical poverty rates and zakat distribution across Malaysian states.
- Identify trends and patterns using Exploratory Data Analysis (EDA).
- Develop machine learning models to predict poverty rates.
- Evaluate and compare model performance.
- Explore how predictive analytics can support poverty analysis and welfare planning.

## 📊 Datasets

The project uses two datasets covering the period **2007–2022**:

1. **Poverty Data** — State-level poverty rates in Malaysia, sourced from the Department of Statistics Malaysia (DOSM).
2. **Zakat Distribution Data** — State-level zakat distribution figures, sourced from the Department of Waqf, Zakat and Hajj (JAWHAR).

The datasets are integrated using **Year** and **State** as common variables.

### Data Sources

- [OpenDOSM / Department of Statistics Malaysia](https://open.dosm.gov.my/)
- [JAWHAR – Zakat Distribution Statistics by State](https://baitulmal.jawhar.gov.my/statistik-agihan-zakat-mengikut-negeri/)

## 🛠️ Tools and Technologies

- **Python** — Data analysis and machine learning
- **Google Colab** — Development environment
- **Pandas and NumPy** — Data cleaning and manipulation
- **Matplotlib** — Data visualization
- **Scikit-learn** — Machine learning models and evaluation
- **Statsmodels** — Statistical analysis and regression results

## ⚙️ Methodology

### 1. Data Collection and Preprocessing
- Collected poverty and zakat distribution datasets.
- Standardized column names and state values.
- Formatted dates and extracted the year.
- Checked data quality and missing values.
- Merged datasets using Year and State.

### 2. Exploratory Data Analysis (EDA)
- Examined descriptive statistics, including mean, minimum, maximum, and standard deviation.
- Visualized poverty rates and zakat distribution across states.
- Analyzed historical trends using line charts and bar charts.
- Explored the relationship between poverty rates and zakat distribution using scatter plots.

### 3. Feature Selection

The selected variables are:

| Variable | Role |
|---|---|
| Year | Predictor |
| Total Zakat Distribution | Predictor |
| Poverty Rate | Target variable |
| State | Descriptive and grouping variable |

### 4. Predictive Modeling

Two regression models are developed and compared:

- **Multiple Linear Regression** — Models the relationship between poverty rates, year, and total zakat distribution.
- **Decision Tree Regression** — Captures potential nonlinear patterns in the data.

### 5. Model Evaluation

Model performance is evaluated using:

- **Mean Absolute Error (MAE)** — Measures the average absolute prediction error.
- **Root Mean Squared Error (RMSE)** — Measures prediction error while penalizing larger errors.
- **R² Score** — Measures how well the model explains variation in the target variable.

Regression coefficients, t-statistics, and p-values are also examined for the Multiple Linear Regression model.

## 📈 Expected Outcomes

- Insights into historical poverty trends across Malaysian states.
- An overview of zakat distribution patterns over time.
- A comparison of two machine learning regression models.
- Predictions and exploratory projections of poverty rates to support further analysis and welfare planning.

**Note:** The analysis uses state-level data and identifies statistical patterns. It does not establish that zakat distribution directly causes changes in poverty rates.

## 🚀 How to Run

1. Clone or download this repository.
2. Open the Jupyter Notebook (`.ipynb`) in Google Colab or a compatible Jupyter environment.
3. Install the required Python libraries if they are not already available:

   ```bash
   pip install pandas numpy matplotlib scikit-learn statsmodels
   ```

4. Upload or configure the datasets according to the file paths used in the notebook.
5. Run the notebook cells sequentially to reproduce the data preprocessing, visualizations, model training, and evaluation.
