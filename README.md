# Interconnect Project

## Overview
This project explores and analyzes data related to user behaviour and compares different models for customer churn prediction.

## Features
- **Data loading:** Loading data from several csv files into DataFrames using pandas.
- **EDA:** Comprehensive Exploratory Data Analysis including bar plots, histograms, time series using seaborn, matplotlib, pandas, missingno among others.
- **Model comparision:** Implementing and comparing different machine learning pipelines for classification using sklearn. The models to be compared are: XGBoost and LogisticRegression. Soon artificial neural networks will be included in the comparision.
- **Bussiness metrics:** Calculating the impact of our predictions in terms of customers kept and its contribution in maximizing income. THIS SECTION WILL BE ADDED SOON


## How to Use
1. Clone this repository or download the notebook.
2. Ensure you have the required dependencies (see below).
3. Open `interconnect.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells sequentially to reproduce the analysis and results.

## Requirements
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- missingno
- XGBoost

## Data
The analysis uses datasets located in the `datasets/` directory. Please refer to the notebook for details on each dataset used.

## Project Structure
```
interconnect/
├── interconnect.ipynb
├── datasets/
└── README.md
```

## Results
- After training, our models had a ROC-AUC higher than 0.7
- XGBoost had better performance with a ROC-AUC close to 0.89
- Class balancing techniques were applied due to the poor balance seen in our target variable.
- Several insights found in EDA. Please refer to the jupyter notebook

