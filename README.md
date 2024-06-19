# PUBG Game Prediction

Welcome to the PUBG Game Prediction project! This repository contains code and resources to predict the outcome of PUBG games based on various player and game parameters using machine learning.

![PUBG Game](https://drive.google.com/uc?id=1v8MifS2z7clZ1vJaHGLIrNVn5iIooVPL)

## Dataset Information

The dataset contains 29 features that describe various aspects of a PUBG game and player performance. Each feature will be explained in the project video to provide context and understanding.

## Data Wrangling

Data wrangling is crucial for preparing the dataset for machine learning. Tasks include:

- Removing unnecessary columns
- Handling missing values (e.g., imputation or dropping rows)
- Converting categorical data to numerical form (e.g., using one-hot encoding)
- Splitting the data into training and testing sets

These steps ensure that the data is in a suitable format for training machine learning models.

## Feature Engineering

Feature engineering involves creating new features or transforming existing ones to improve model performance. For the PUBG win prediction model, this might include:

- Normalizing features
- Dropping irrelevant features to reduce model complexity
- Creating new features based on combinations of existing features (e.g., total kills per game)

## CatBoost Model

CatBoost is chosen for this dataset due to its effectiveness with categorical data, speed, ease of use, and accuracy:

- **Effective with Categorical Data:** CatBoost handles categorical features well, automatically encoding them numerically and managing missing values.
  
- **Fast and Easy to Use:** Training CatBoost models is typically fast, and it supports features like automatic handling of missing data and parallelization.
  
- **Powerful and Accurate:** CatBoost, as a gradient boosting algorithm, is known for its accuracy and has been successful in various machine learning competitions.

### Performance Evaluation

The performance of the CatBoost model will be evaluated using Root Mean Squared Error (RMSE) to measure prediction accuracy.

## Visualization and Exploratory Data Analysis (EDA)

EDA will provide insights into the dataset and PUBG game dynamics. Visualizations such as graphs and plots will aid in understanding player behaviors and game characteristics.

### Example Graphs

- Histograms showing distribution of key features (e.g., kills, rank)
- Scatter plots to explore correlations between variables
- Bar charts for categorical variables (e.g., types of weapons used)

## Usage

1. Clone the repository and navigate to the project directory.
2. Install dependencies listed in requirements.txt.
3. Follow the Jupyter notebooks or Python scripts for data preprocessing, EDA, feature engineering, model training with CatBoost, and performance evaluation.
