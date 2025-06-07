# Data-Driven-Insights-into-the-US-Housing-Market

# Modeling Economic Influences on U.S. Housing Prices (2000–2023)

## 📌 Objective
This project explores how key economic and demographic factors have influenced U.S. home prices over the last 20 years. Using the S&P Case-Shiller Index as a proxy for housing prices, the project builds and compares multiple regression models to predict and interpret historical trends.

---

## 📊 Project Workflow

### 1. Data Collection
- Used **S&P Case-Shiller Home Price Index** from [FRED](https://fred.stlouisfed.org/series/CSUSHPISA).
- Supplemented with economic and social indicators from FRED and World Bank.

### 2. Influencing Variables
- **Economic Metrics:** GDP per Capita, CPI, Median Income, Construction Prices, Interest Rates
- **Labor Market:** Employment Rate, Unemployment Rate, Working-age Population
- **Demographics:** Urban Population %, Population above 65, Total Households
- **Policy & Supply:** Housing Subsidies, Number of New Houses Supplied

### 3. Data Preprocessing
- Cleaned and transformed data
- Addressed missing values and outliers
- Converted date formats and ensured time alignment

### 4. Exploratory Data Analysis (EDA)
- Visualized time trends and distributions
- Identified correlations and feature interdependencies

### 5. Model Building
- Trained and evaluated the following models:
  - Linear Regression
  - ElasticNet
  - Random Forest Regressor
  - Gradient Boosting Regressor
  - Support Vector Regressor (SVR)
  - XGBoost

### 6. Model Evaluation
- Metrics: **Mean Squared Error (MSE)** and **R-squared (R²)**
- Cross-validation for robustness

### 7. Feature Importance Analysis
- Interpreted tree-based models (Random Forest, XGBoost)
- Identified most influential predictors

### 8. Visualization
- Actual vs. Predicted prices
- Feature importance plots
- Temporal trends and model insights

---

## ✅ Results
- Tree-based models like **XGBoost** outperformed others in accuracy.
- Top predictors included **Interest Rates**, **GDP per Capita**, and **Urban Population Share**.
- The model provides both predictive insight and explanatory value for policy and investment decisions.

---

## 🗂️ Data Sources

| Variable                        | Source Link |
|-------------------------------|-------------|
| Case-Shiller Index            | https://fred.stlouisfed.org/series/CSUSHPISA |
| Interest Rates                | https://fred.stlouisfed.org/series/FEDFUNDS |
| CPI                           | https://fred.stlouisfed.org/series/CPIAUCSL |
| GDP per Capita                | https://fred.stlouisfed.org/series/A939RX0Q048SBEA |
| Real Median Household Income | https://fred.stlouisfed.org/series/MEHOINUSA672N |
| Urban Population (%)         | https://data.worldbank.org/indicator/SP.URB.TOTL.IN.ZS |
| Housing Subsidies (Federal)  | https://fred.stlouisfed.org/series/L312051A027NBEA |
| Total Households             | https://fred.stlouisfed.org/series/TTLHH |
| Construction Prices          | https://fred.stlouisfed.org/series/WPUSI012011 |

---

## 📚 References

- [Investopedia – Understanding the Case-Shiller Index](https://www.investopedia.com/articles/mortgages-real-estate/10/understanding-case-shiller-index.asp)
- [Atlantis Press – Research Paper](https://www.atlantis-press.com/article/25841966.pdf)

---

## 📌 Conclusion

This analysis not only demonstrates how economic indicators influence U.S. housing prices but also builds a solid foundation for applying machine learning to real estate forecasting and economic policy planning.
