# Weather-Related Disease Prediction

This project uses machine learning to predict disease prognosis based on patient symptoms and environmental weather conditions.

## Project Overview

The goal of this project was to determine whether clinical symptoms and weather-related variables could be used to predict likely disease outcomes. The dataset included patient symptom records, demographic variables, and weather conditions.

This project was completed as part of PSTAT 134 at the University of California, Santa Barbara.

## Dataset

Source: Kaggle Weather-Related Disease Prediction Dataset

The dataset included:

- 5,200 observations
- 51 total variables
- 50 predictor variables
- 1 response variable: disease prognosis
- Patient symptoms such as cough, headache, vomiting, dizziness, and chest pain
- Weather variables such as temperature, humidity, and wind speed

## Methods Used

The project compared several machine learning approaches:

- Exploratory Data Analysis
- Multinomial Logistic Regression
- Penalized Regression
- Neural Networks
- Decision Trees
- Random Forest
- XGBoost

## Key Results

XGBoost produced the strongest overall performance, with an accuracy of approximately 98.9%.

The neural network model also performed strongly, with an accuracy of approximately 95.7%.

Weather-related variables were not major predictors of disease prognosis. Patient symptoms were generally more important for classification.

## Files in This Repository

- `Weather_Disease_Prediction.ipynb` — main project notebook
- `Final_Report.pdf` — written project report
- `Project_Presentation.pptx` — final presentation slides
- `.png` files — charts and model output images used in the report and presentation

## Tools and Skills Demonstrated

- Python
- Jupyter Notebook
- Machine Learning
- Classification Models
- Exploratory Data Analysis
- Healthcare Analytics
- Model Evaluation
- Data Visualization

## Notes

This project was completed for academic purposes using a publicly available Kaggle dataset.
