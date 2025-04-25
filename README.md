# Sales Prediction Project

This repository contains a machine learning project for predicting car purchase amounts based on customer data. The project includes data preprocessing, model training, and evaluation.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

---

## Project Overview
The goal of this project is to predict the amount a customer is likely to spend on a car purchase based on features such as age, annual salary, credit card debt, and net worth. The project uses machine learning models like Linear Regression.

---

## Dataset
The dataset used in this project is `car_purchasing.csv`, which contains the following columns:
- `Customer Name`
- `Customer Email`
- `Country`
- `Gender`
- `Age`
- `Annual Salary`
- `Credit Card Debt`
- `Net Worth`
- `Car Purchase Amount`

The dataset is located in the https://github.com/piyush814325/Car-Sales-Prediction/blob/main/car_purchasing.csv

---

## Methodology
1. **Data Collection**:
   - Load the dataset and inspect its structure.

2. **Data Preprocessing**:
   - Handle missing values.
   - Remove irrelevant columns (e.g., `Customer Name`, `Customer Email`, `Country`).
   - Standardize numerical features.
   - Remove outliers using the Interquartile Range (IQR) method.

3. **Feature Engineering**:
   - Select relevant features for the model.

4. **Model Training**:
   - Train models like Linear Regression.
   - Split the data into training and testing sets.

5. **Model Evaluation**:
   - Evaluate models using metrics like R-squared, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
   - Visualize actual vs. predicted values.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/piyush814325/Car-Sales-Prediction.git
   cd sales-prediction
