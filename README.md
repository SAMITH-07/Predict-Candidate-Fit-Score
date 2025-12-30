# Predict-Candidate-Fit-Score

## Overview
This project focuses on building a machine learning model to predict a **Candidate Fit Score** based on key attributes such as experience, skills, education level, and test performance. The goal is to support **data-driven hiring decisions** by quantifying how well a candidate matches a role.

Since no dataset was provided, a **synthetic dataset** was generated to demonstrate the full machine learning workflow.

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- scikit-learn  
- Matplotlib  

---

## Project Objective
The main objectives of this project are:
- To predict a candidate’s fit score using machine learning  
- To understand which factors influence hiring decisions the most  
- To compare different regression models for performance  
- To provide explainable insights using feature importance  

---

## Dataset Description
- Synthetic dataset with 200 candidate records  
- Features include:
  - Experience (years)
  - Skill score
  - Education level
  - Test score
- Target variable:
  - Fit Score (continuous value)
- Dataset is clean with no missing values

---

## Data Preparation
The following steps were performed:
- Generated synthetic candidate data
- Selected relevant features and target variable
- Split data into training and testing sets
- Applied feature scaling where required

---

## Methodology
Two regression models were implemented and compared:

### 1. Linear Regression
- Serves as a baseline model
- Assumes linear relationships between features and fit score

### 2. Random Forest Regressor
- Captures non-linear relationships
- Provides feature importance for explainability
- Achieved better performance than Linear Regression

---

## Model Evaluation
Models were evaluated using:
- Mean Squared Error (MSE)
- R² Score

Random Forest showed improved accuracy and better generalization compared to Linear Regression.

---

## Feature Importance
Feature importance analysis revealed:
- Skill score and test score have the highest impact
- Experience also plays a significant role
- Education level has comparatively lower influence

This insight helps recruiters prioritize the most relevant candidate attributes.

---

## Key Observations
- Candidate suitability can be effectively predicted using structured data
- Non-linear models perform better for real-world hiring scenarios
- Feature importance adds transparency to model predictions

---

## Conclusion
This project demonstrates how machine learning can be used to predict candidate fit scores and assist hiring teams in making objective decisions. The approach is scalable and can be extended with real candidate data, additional features, and advanced models.

---

## Demo
Google Colab Notebook:  
[https://colab.research.google.com/drive/1cdUHjAidNmrDHMAjxSMQk_rEOGl1bZEz?usp=sharing](https://colab.research.google.com/drive/1_oZhCGHSpC5NWpgIRhWicBfNjypAg8oI?usp=sharing)

---

## Notes
- Synthetic data was used due to the absence of a real dataset
- This project is intended for learning and demonstration purposes
