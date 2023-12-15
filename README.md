# TechValuPredict - Laptop Price Prediction System

## Overview

TechValuPredict is a machine learning-based system for predicting laptop prices. It incorporates various regression algorithms, including Random Forest, Decision Tree, Lasso, Ridge, and Linear Regression, to provide users with accurate price estimations.

## Dependencies

Ensure dependencies are installed using:

```bash
pip install -r requirements.txt
streamlit~=1.12.0
sklearn
pip~=21.2.3
toml~=0.10.2
tornado~=6.2
setuptools~=57.4.0
pandas~=1.5.3
numpy~=1.24.2
Usage
To run the Laptop Price Prediction System:

```bash
streamlit run laptop_price_predictor.py

This opens a web interface allowing users to input laptop specifications and receive a predicted price range.

Machine Learning Algorithms
The system uses the following regression algorithms:

Random Forest Regressor: An ensemble learning method combining multiple decision trees for improved accuracy and robustness.

Decision Tree Regression: A model that makes decisions based on the features of the input data, forming a tree-like structure.

Lasso Regression: Linear regression with L1 regularization, useful for feature selection and preventing overfitting.

Ridge Regression: Linear regression with L2 regularization, addressing multicollinearity in the input data.

Linear Regression: A straightforward approach modeling the relationship between the dependent and independent variables.

Model Loading
The system loads a pre-trained machine learning model (pipe.pkl) during runtime, ensuring quick and accurate predictions.

Input Parameters
Users can input the following laptop specifications for prediction:

Brand
Type
RAM (in GB)
OS
Weight
Touchscreen
IPS (In-Plane Switching)
Screen Size
Screen Resolution
CPU
HDD (in GB)
SSD (in GB)
GPU
Prediction
Clicking the "Predict Price" button provides users with a predicted price range based on the entered specifications.

Note
TechValuPredict leverages advanced regression techniques, enabling users to make informed decisions in the competitive laptop market. Explore and harness the power of machine learning for accurate laptop price predictions!
