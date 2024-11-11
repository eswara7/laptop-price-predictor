# 💻 laptop price predictor

A machine learning-based web app to predict the price of a laptop based on its specifications. Given features like brand, processor, RAM, weight, and other laptop specifications, the app provides an estimated price. This project uses Streamlit for the frontend and a Random Forest Regressor model to make price predictions.

## 🛠️ Project Overview

In this project, we developed a predictive model that estimates laptop prices from user-provided specifications. Using a dataset containing various laptop features (brand, RAM, screen size, etc.), we cleaned the data, performed feature engineering, and trained a regression model to predict laptop prices.

## 🔍 Data Processing

Key data preprocessing steps include:

1. **Data Cleaning**: Removing missing values, duplicates, and irrelevant columns.
2. **Feature Engineering**: Extracting key features such as PPI (Pixels Per Inch) from screen resolution and categorizing CPU brands.
3. **Encoding Categorical Data**: Encoding categorical variables using OneHotEncoder for machine learning.
4. **Feature Scaling**: Normalizing numerical features like RAM, weight, and storage.

## 📊 Model Building

We used the following steps for model development:

- **Random Forest Regressor**: The core model that predicts the laptop price based on features such as processor type, RAM, weight, and more.
- **Pipeline**: The `Pipeline` class is used to combine preprocessing and modeling steps for a streamlined workflow.
- **Model Evaluation**: Evaluated the model using Mean Absolute Error (MAE) and other metrics.

## 🤖 Web App with Streamlit

This project also includes a user-friendly web app built using Streamlit. The app allows users to input laptop specifications and predicts the laptop price.

### Features:
- **Brand, Type, and CPU**: Select the laptop's brand, type, and CPU brand.
- **RAM, Weight, and Screen Size**: Input the laptop’s RAM, weight, and screen size.
- **Touchscreen, IPS, and Storage**: Choose whether the laptop has a touchscreen, IPS display, and input the HDD/SSD storage capacities.
- **Prediction**: After filling out the form, click the **Predict Price** button to receive an estimated laptop price.

## 🚀 Skills Developed

This project helps develop skills in:

- **Python Programming** 🐍
- **Machine Learning** 🤖
- **Data Cleaning & Feature Engineering** 🧹
- **Data Visualization** 📊
- **Web Development with Streamlit** 🌐