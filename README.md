# USA Used Car Price Prediction

Predicting used car prices in the USA using machine learning with Azure Databricks and a Streamlit app.

![Project Logo](https://github.com/tmahesh20/Group-4-FINAL-PROJECT/blob/main/logo.png)

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data](#data)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Machine Learning Models](#machine-learning-models)
- [Streamlit App](#streamlit-app)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Welcome to the USA Used Car Price Prediction project! This project is designed to assist users in predicting the prices of used cars across the USA through the application of advanced machine learning techniques. Whether you're a car enthusiast or a data science enthusiast, this project offers valuable insights into the factors that influence used car prices and showcases the power of data-driven predictions.

## Features

- **Data Preprocessing:** Cleaned and prepared the dataset using PySpark on Azure Databricks for optimal analysis.
- **Exploratory Data Analysis:** Explored the dataset using Python's data analysis libraries to gain insights.
- **Model Selection:** Explored and selected the best machine learning model for prediction.
- **Prediction:** Predict used car prices with user-provided features.
- **User-Friendly Interface:** User interface for easy interaction with the model using the Streamlit app.


## Installation

Follow these steps to get the project up and running on your local machine:

Clone the repository:
   ```bash
   git clone https://github.com/yourusername/usa-used-car-prediction.git
   cd usa-used-car-prediction
   ```

## Data
The dataset used for this project was sourced from [https://www.kaggle.com/datasets/ananaymital/us-used-cars-dataset/code]. It contains information about various cars, including their make, model, year, mileage, and more. The dataset was preprocessed using PySpark on Azure Databricks to handle missing values and outliers.

## Exploratory Data Analysis (EDA)
The exploratory data analysis was conducted using Python's data analysis libraries such as Pandas, Matplotlib, and Seaborn. The notebook eda.ipynb provides insights into the relationships between car features and prices.

## Machine Learning Models
We used various machine learning models, including [Linear Regressor, Random Forest Regressor, LightGBM, XGBoost], to build predictive models. The model with the best performance was selected for prediction. You can find the implementation details in the Model.ipynb script.

## Streamlit App
The Streamlit app, app.py, allows users to easily interact with the trained machine learning model.

## Results
Our trained model achieved an accuracy of [92%]. This indicates the model's ability to predict used car prices effectively.

## Contributing
Contributions are welcome! To contribute to this project, follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your enhancements or fixes.
4. Submit a pull request.

## License
This project is licensed under the MIT License.
```vbnet

In this updated version of the README, I've added a new section for the Streamlit app, and you can include a description and screenshots of how users can use the app to interact with your trained machine learning model. Make sure to replace placeholders with actual information and include relevant files like `app_streamlit.py`.
```
