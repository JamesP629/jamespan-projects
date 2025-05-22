**Diabetes Predictive Analysis Project**

This project trains and uses 5 different models to predict whether or not a patient has diabetes. The goal of this project is to help diagnose diabetes early, which would allow the patients to get ahead of the disease and make those lifestyle changes to reduce the impact of diabetes on their life. The dataset chosen is a collection of survey results that contain possible diabetes indicators and whether or not the patient has diabetes. 

Kaggle Dataset: https://www.kaggle.com/datasets/alexteboul/diabetes-health-indicators-dataset
##Tools and Libraries used

- **R**
  - `caret` – Model training and evaluation
  - `ggplot2` – Visualizations
  - `dplyr` – Data manipulation
  - `class` – KNN classification
  - `janitor` – Data cleaning
  - `C50` – Decision tree modeling 

## Model Overview

The following models were trained and used for this project:

- Logistic Regression
- K-Nearest Neighbours (KNN)
- Artifical Nueral Network (ANN)
- Decision Tree (c5.0)
- Random Forest
- Combined Model

### Model Performance Summary
| Model              | Accuracy | Sensitivity | Specificity  | 
|-------------------|----------|-------------|---------------|
| Logistic Regression | 0.8662   | 0.1264      | 0.9869      |
| KNN                 | 0.8450   | 0.2023      | 0.9499      | 
| ANN                 | 0.8666   | 0.1560      | 0.9825      |
| Decision Tree       | 0.7715   | 0.6723      | 0.8723      |
| Random Forest       | 0.8652   | 0.1376      | 0.9830      | 
| Combined Model      | 0.7401   | 0.7707      | 0.7095      |

## Applications
- Prediction of other diseases using classifcation models
- Tradeoffs between sensitivity and specificity for diagnoses

## Project Files
- 'DiabetesAnalaysis.RMD' - R markdown report including the models and their visualizations
- 'ann_pred_raw.csv' - CSV file containing the results of the ANN Prediction Model
- 'knn_pred.csv' - CSV file containing the results of the KNN Prediction Model
- 'DecisionTree.csv' - CSV file containing the results of the Decision Tree Model
- 'randomForestFIXED.csv' - CSV file containing the results of the Random Forest Model
- 'diabetesmodel-19660.twbr' - Tableau dashboard visualizing prediction and metrics
