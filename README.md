---

## Linear Regression Models Implementation Readme

### Overview

This repository contains implementations of Linear Regression models using Python and the scikit-learn library. Two main models have been built:

1. **Model 1: Single Variable Linear Regression**
   - **Dataset:** Utilizes a dataset `homeprices.csv` containing columns: `area` and `price`.
   - **Description:** Performs simple linear regression using the area to predict the price of houses.
   - **Steps:**
     - Data visualization through scatter plots.
     - Training a Linear Regression model.
     - Predicting prices for new areas.
     - Exporting predictions to `prediction.csv`.
  
2. **Model 2: Multiple Variable Linear Regression**
   - **Dataset:** Uses `homeprices.csv` with additional features: `area`, `bedrooms`, `age`, and `price`.
   - **Description:** Implements multiple variable regression to predict house prices considering area, bedrooms, and age.
   - **Steps:**
     - Data preprocessing: Handling missing values in the `bedrooms` column.
     - Training a Multiple Variable Linear Regression model.
     - Predicting prices for different house configurations.

### Usage

#### Libraries Used
- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `matplotlib`: For data visualization.
- `scikit-learn`: For implementing the Linear Regression models.

#### Files
- `homeprices.csv`: Dataset containing house price-related information.
- `areas.csv`: Contains new areas for predicting prices.

#### Instructions
1. **Model 1:**
   - Run the code for Single Variable Linear Regression.
   - Check `prediction.csv` for predicted prices of houses with new areas.

2. **Model 2:**
   - Execute the code for Multiple Variable Linear Regression.
   - Predict prices for houses with various area, bedrooms, and age combinations.

### Notes
- Ensure all necessary libraries are installed.
- Verify data file paths before running the code.
- Take note of warnings or errors that might occur during model training or prediction.

### Author
Mridul Srivastava
mridulsrivastava101@gmail.com
91+ 7705982560

---
