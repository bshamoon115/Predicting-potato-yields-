# 🥔 Predicting Potato Yields using Machine Learning

This project uses a simple linear regression model to predict **potato yield (kg/acre)** based on fertilizer inputs and other agricultural parameters. It's built in Python using scikit-learn and tested on Google Colab.

## 📂 Dataset

The dataset used is a CSV file named `fertilizers.csv` which includes features such as:
- Fertilizer quantity
- Rainfall (mm)
- Temperature or time (assumed from context)

The target variable is **potato yield**.

## 📊 Technologies Used

- Python
- Pandas & NumPy
- scikit-learn
- Matplotlib (for potential visualizations)
- Google Colab

## 📌 How the Model Works

1. Load and clean the dataset (`fertilizers.csv`)
2. Split the data into training and testing sets (67%-33%)
3. Train a **Linear Regression** model on the training data
4. Predict the yield for both test data and new custom input
5. Output a predticing resault
