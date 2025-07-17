# 🥔 Potato Yield Prediction

This project uses regression analysis to predict potato crop yields based on agricultural features such as rainfall, temperature, and fertilizer use. It demonstrates how machine learning can assist in precision agriculture and improve crop planning and resource allocation.

---

## 📌 Objective

To estimate potato yield (in tons per hectare) using key environmental and farming-related variables with a supervised machine learning regression model.

---

## 📊 Dataset

The dataset includes the following features:

- `Area (acres)` – Cultivated land area
- `Rainfall (mm)` – Total rainfall received during the growing season
- `Temperature (°C)` – Average temperature
- `Fertilizer Used (kg)` – Amount of fertilizer applied
- `Yield (tons)` – Actual potato yield (target variable)

> *Note: Dataset is either synthetic or adapted from publicly available agricultural sources.*

---

## 🧠 Machine Learning Workflow

1. **Data Preprocessing**
   - Handled missing values
   - Normalized/standardized features

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmap
   - Pairplots for feature relationships
   - Distribution plots

3. **Modeling**
   - Used **Linear Regression** (you can later compare with Random Forest or XGBoost)

4. **Model Evaluation**
   - R² Score
   - Mean Squared Error (MSE)
   - Actual vs Predicted Yield plot

---

## 🔧 Libraries & Tools Used

- `pandas` for data manipulation  
- `matplotlib` & `seaborn` for visualization  
- `scikit-learn` for ML modeling and evaluation  
- `jupyter notebook` for running and documenting the project

---

## 📈 Results

- **R² Score**: ~0.78 (example)
- The model was able to predict yield within a reasonable margin for most test samples.
- Rainfall and fertilizer showed strong correlation with higher yield.



---

## 🏷️ Tags

`potato-yield` `regression` `machine-learning` `agriculture` `data-science` `scikit-learn` `jupyter-notebook` `crop-prediction`

---
