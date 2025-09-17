# House Price Prediction - Advanced Regression Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange)
![XGBoost](https://img.shields.io/badge/Model-XGBoost-green)
![SHAP](https://img.shields.io/badge/Interpretability-SHAP-red)

## 📖 Project Overview

This project aims to build a robust machine learning model to predict the final sale price of residential homes in Ames, Iowa. The model is based on a comprehensive dataset containing 79 explanatory variables describing various aspects of the properties. The goal is to demonstrate a complete end-to-end data science workflow, from data exploration and cleaning to model interpretation and insight generation.

## 📊 Dataset

The dataset is from the famous [House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques) Kaggle competition.
- **train.csv** - The training set (1460 observations)
- **test.csv** - The test set (1459 observations)

## 🛠️ Technical Skills Demonstrated

- **Programming Language:** Python
- **Data Manipulation & Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Machine Learning:** Scikit-learn, XGBoost
- **Model Interpretation:** SHAP (SHapley Additive exPlanations)
- **Development Environment:** Jupyter Notebook

## 📈 Results and Insights

The XGBoost regression model was the top performer. Key drivers of house prices were found to be:
1.  **Overall Quality** of the property.
2.  **Above Ground Living Area** square footage.
3.  The **Neighborhood** of the property.
4.  The **Year the house was built** and the **Year the garage was built**.

SHAP value analysis was used to interpret the model's predictions and confirm these global feature importances.

## 🚀 How to Run This Project

1.  **Clone this repository:**
    ```bash
    git clone https://github.com/HiraAashir/House-Price-Prediction-ML.git
    ```
2.  **Navigate to the project directory:**
    ```bash
    cd House-Price-Prediction-ML
    ```
3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Open and run the Jupyter Notebook:**
    ```bash
    jupyter notebook notebooks/house_price_prediction.ipynb
    ```

## 📁 Project Structure
