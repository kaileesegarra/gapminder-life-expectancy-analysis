# Global Life Expectancy Trends: A Regression Analysis of Gapminder Data

**Kailee Segarra**  
CMPS 6790 – Data Science  

---

## Project Overview

This project analyzes global life expectancy trends using the Gapminder dataset. The goal is to understand how life expectancy has changed over time and how factors such as continent influence these trends.

The project includes:
- Exploratory Data Analysis (EDA)
- Linear regression modeling
- Residual analysis
- Interaction effects (continent × year)
- Classification using machine learning models

---

## Dataset

- Source: Gapminder dataset  
- Features include:
  - Year
  - Life expectancy
  - Country
  - Continent
  - GDP per capita
  - Population

---

## Key Findings

**- Life expectancy has increased steadily over time across all regions.**
**- There are clear differences in trends between continents.**
**- Including interaction terms improves model performance.**
**- Random Forest slightly outperforms Decision Tree in classification tasks.**

---

## Methods Used

- Python (Pandas, NumPy)
- Data visualization (Matplotlib, Seaborn)
- Linear Regression (Scikit-learn, Statsmodels)
- Machine Learning (Random Forest, Decision Tree)
- Cross-validation for model evaluation

---

## Models

### Regression
- Simple linear regression: `lifeExp ~ year`
- Interaction model: `lifeExp ~ year * continent`

### Classification
- Random Forest
- Decision Tree

---

## Results

**- Linear model shows a strong positive relationship between year and life expectancy.**
**- Interaction model improves fit (higher explanatory power).**
**- Random Forest achieves higher accuracy (~0.97) than Decision Tree (~0.95).**

---

## How to Run

1. Open the notebook in Google Colab or Jupyter
2. Run all cells in order
3. No additional setup required

---

## Future Improvements

- Incorporate additional variables (GDP, population)
- Explore non-linear models
- Perform deeper statistical testing

---

## Author

Kailee Segarra  
