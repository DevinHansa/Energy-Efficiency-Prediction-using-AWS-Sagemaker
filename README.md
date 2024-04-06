# Building Energy Efficiency Prediction using AWS Sagemaker(Supervised Learning)

## Overview
This project aims to predict the energy efficiency rating of buildings based on features like wall area, roof area, overall height, etc. The model is built using supervised learning techniques, particularly utilizing the Random Forest algorithm. 

## Dataset
A synthetic dataset is generated to simulate building features and energy efficiency ratings. The dataset includes features such as Wall Area, Roof Area, Overall Height, and Glazing Area. Energy efficiency ratings are represented by the 'EnergyEfficiency' column. 

## Implementation
The project is implemented using Python and AWS Sagemaker. Below are the main steps:

### 1. Importing Libraries
Necessary libraries including Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn are imported.

### 2. Data Preprocessing
The dataset is preprocessed by splitting it into features (X) and the target variable (y).

### 3. Exploratory Data Analysis (EDA)
Relationships between features and the target variable are visualized using scatter plots.

### 4. Model Training
The dataset is split into training and testing sets. Then, a Random Forest Regressor model is trained using the training data.

### 5. Prediction and Evaluation
The trained model is used to predict energy efficiency ratings on the testing set. Mean Squared Error (MSE) is computed to evaluate the model's performance.

### 6. Visualization
The true values vs predicted values are plotted to visualize the performance of the model.

## Dependencies
- Python 3
- AWS Sagemaker
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
