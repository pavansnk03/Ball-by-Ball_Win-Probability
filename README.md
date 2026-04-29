# Ball-by-Ball Win Probability

A reproducible Python project for estimating ball-by-ball win probability for chasing teams in Men’s T20 World Cup matches.  
The pipeline converts Cricsheet YAML data into structured ball-by-ball CSV files, engineers match-state features, and compares statistical, machine learning, and deep learning models for win probability prediction. :contentReference[oaicite:0]{index=0}

## Project Overview

This project focuses on second-innings chase situations in Men’s T20 World Cup matches.  
It builds a complete workflow from raw YAML match files to cleaned CSV datasets, feature engineering, exploratory analysis, model training, and evaluation.

## Objectives

- Convert raw Cricsheet YAML files into structured match and delivery datasets
- Clean and filter completed Men’s T20 World Cup matches
- Engineer match-state features such as current run rate, required run rate, balls remaining, and wickets lost
- Compare statistical, machine learning, and deep learning models
- Visualize match patterns and model performance

## Dataset

The project uses ball-by-ball cricket data from Cricsheet and includes completed Men’s T20 World Cup matches.  
The dissertation pipeline covers YAML extraction, CSV conversion, feature engineering, and model-ready dataset creation. :contentReference[oaicite:1]{index=1}

## Workflow

1. Load raw YAML files
2. Filter only Men’s T20 World Cup matches
3. Remove tied, abandoned, curtailed, and no-result matches
4. Convert nested YAML structure into ball-by-ball CSV format
5. Create engineered features
6. Perform exploratory data analysis
7. Train and compare models
8. Evaluate predictions using metrics such as Accuracy, Log Loss, ROC AUC, MSE, and RMSE

## Features Engineered

- Current Run Rate
- Required Run Rate
- Balls Remaining
- Cumulative Runs
- Cumulative Wickets
- Match Phase
- Boundary and dot-ball indicators

## Models Used

### Statistical Models
- Mean Regressor
- Ordinary Least Squares
- Linear Regression

### Machine Learning Models
- Random Forest
- XGBoost
- SVR

### Deep Learning Models
- MLP
- GRU
- LSTM

## Tech Stack

- Python
- pandas
- numpy
- scikit-learn
- statsmodels
- TensorFlow / Keras
- Plotly
- Matplotlib
- Seaborn

## Repository Structure

```text
Ball-by-Ball-Win-Probability/
│
├── Codebase/
│   └── main notebook / scripts
├── YAML FILES/
│   └── raw or filtered YAML match files
├── images/
│   └── plots, charts, and result figures
├── Pavan_24P0630010_final_thesis.pdf
└── README.md
