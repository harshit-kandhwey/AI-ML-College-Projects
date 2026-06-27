# Linear Regression — Climate Change

Analysis of global temperature trends (May 1985 – Dec 2005) using linear regression, exploring the relationship between time and rising temperatures.

---

## Overview

Climate change is driven by greenhouse gas emissions — primarily CO₂ and methane — which amplify global warming through feedback mechanisms. This project focuses on one measurable impact: **rising temperatures over time**.

Using historical climate data, the project applies linear regression to model and visualize the year-vs-temperature relationship.

---

## Dataset

Source: [Kaggle — Rise in Temperature Dataset](https://www.kaggle.com/vageeshabudanur/riseintemp-dataset)

File: `climate_change.csv`

Available columns: `Year`, `Month`, `MEI`, `CO2`, `CH4`, `N2O`, `CFC-11`, `CFC-12`, `TSI`, `Aerosols`, `Temp`

This project uses `Year` and `Temp` for a univariate regression.

---

## Approach

1. Load and preprocess the CSV with Pandas
2. Visualize temperature trends with Matplotlib
3. Fit a linear regression model: `Temp = a + b * Year`
4. Evaluate model fit and plot the regression line

---

## Dependencies

```
numpy
pandas
matplotlib
scikit-learn
```

Install with:

```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## Getting Started

1. Clone the repository
2. Install dependencies (see above)
3. Open `Linear_Regression_climate_change.ipynb` in Jupyter Notebook
4. Run all cells sequentially
