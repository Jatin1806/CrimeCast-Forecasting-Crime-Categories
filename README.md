# CrimeCast-Forecasting-Crime-Categories

## Table of Contents
1. [Project Overview](#project-overview)
2. [Results](#results)
3. [License](#license)
6. [Acknowledgements](#acknowledgements)

## Project Overview
The Crime Category Prediction Challenge involves analyzing a dataset of crime incidents with the goal of predicting the type of crime based on various factors. This project leverages machine learning techniques to uncover patterns in the data and build predictive models that forecast the crime category for each incident. The project serves as a practice exercise to enhance skills in data analysis, feature engineering, and model building.

The dataset used in this project contains information on crime incidents, including incident locations, victim demographics, and other relevant attributes. Each entry represents a unique crime event, and the objective is to predict the crime category based on the provided features.

- **Source**: [![Link to Dataset](https://www.kaggle.com/competitions/crime-cast-forecasting-crime-categories/data)] 
- **Number of Records**: 20000 Records

The final submission notebook, 22f1000801-notebook-t22024.ipynb, contains the following information:

- Exploratory Data Analysis (EDA)
- Feature Engineering
- BaseLine: Dummy Classifier
  - Model 1: Logistic Regression
  - Model 2: K-Nearest Neighbour (KNN)
  - Model 4: Support Vector Machine (SVM)
  - Model 5: Random Forest
  - Model 6: GradientBoostingClassifier
- Cross-Validation of Different Ensemble Models
- Model Comparison
- Hyperparameter Tuning of XGBClassifier
- LightGBM Classifier
  
  
## Results
I secured the highest 'S' grade and achieved 11th rank with an accuracy of 0.96140 on the effective leaderboard of the Kaggle competition for the term May 2024.
- **Accuracy** = 0.96140
  
![Confusion Matrix](images/confusion_matrix.png)

![Model Performance](images/model_performance.png)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


