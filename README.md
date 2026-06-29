# Weather-Related Disease Prediction

This project explores whether patient symptoms and environmental weather conditions can be used to predict disease prognosis using machine learning classification models. Multiple statistical and machine learning approaches were evaluated to determine which models provided the strongest predictive performance.

## Authors

This project was completed by:

- Alexa Gray
- Jacob Hornby
- Adhit Siripurapu
- Ryan Valencia

as part of PSTAT 134 (Statistical Data Science) at the University of California, Santa Barbara.

As part of this team project, I contributed to data analysis, machine learning model development, visualization, and presentation of the project's findings.

## Project Overview

The objective of this project was to determine whether clinical symptoms and weather-related variables could accurately predict disease prognosis. Using a publicly available healthcare dataset, we compared multiple statistical and machine learning approaches to evaluate predictive performance and identify the variables that contributed most to disease classification.

## Project Highlights

- Analyzed over **5,200 patient records** with **50 predictor variables**
- Compared multiple statistical and machine learning classification models
- Achieved approximately **98.9% accuracy** using **Extreme Gradient Boosting (XGBoost)**
- Evaluated the impact of environmental weather variables on disease prognosis
- Demonstrated that patient symptoms were substantially stronger predictors than weather-related variables

## Dataset

The dataset used in this project is publicly available on Kaggle.

**Dataset Source:**
https://www.kaggle.com/datasets/orvile/weather-related-disease-prediction-dataset

After downloading the dataset, place the CSV file in the project directory before running the notebook.

Dataset summary:

- 5,200 observations
- 51 total variables
- 50 predictor variables
- 1 response variable (Disease Prognosis)
- Patient symptoms including cough, headache, vomiting, dizziness, chest pain, and many others
- Weather variables including temperature, humidity, and wind speed

## Getting Started

1. Download the dataset from the Kaggle link above.
2. Place the CSV file in the project directory.
3. Open `Weather_Disease_Prediction.ipynb`.
4. Run the notebook from beginning to end.

## Methods Used

Several statistical and machine learning approaches were evaluated, including:

- Exploratory Data Analysis (EDA)
- Multinomial Logistic Regression
- Penalized Regression (Ridge, Elastic Net, and Lasso)
- Neural Networks
- Decision Trees
- Random Forest
- Extreme Gradient Boosting (XGBoost)

## Key Results

- **XGBoost** produced the strongest overall performance, achieving approximately **98.9% accuracy**.
- The **Neural Network** model also performed well, achieving approximately **95.7% accuracy**.
- Tree-based machine learning models substantially outperformed regression-based approaches.
- Patient symptoms were significantly stronger predictors of disease prognosis than weather-related variables.

## Repository Contents

- `Weather_Disease_Prediction.ipynb` — Complete Jupyter notebook containing data preparation, exploratory analysis, model development, and evaluation.
- `Final_Report.pdf` — Final written project report.
- `Project_Presentation.pptx` — Final presentation summarizing the project and findings.
- `images/` — Figures generated during exploratory analysis, model evaluation, and presentation development.

## Tools and Skills Demonstrated

### Programming & Libraries

- Python
- pandas
- NumPy
- scikit-learn
- XGBoost
- Matplotlib
- Jupyter Notebook

### Data Science Skills

- Machine Learning
- Classification Modeling
- Exploratory Data Analysis
- Healthcare Analytics
- Feature Importance Analysis
- Model Evaluation
- Data Visualization

## Notes

This project was completed as part of PSTAT 134 (Statistical Data Science) at the University of California, Santa Barbara using a publicly available Kaggle dataset.

The purpose of this repository is to showcase the complete project workflow, including exploratory data analysis, predictive modeling, evaluation, and presentation of results.
