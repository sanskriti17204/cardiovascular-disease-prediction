# cardiovascular-disease-prediction

# Data
The dataset consists of 70 000 records of patients data: 11 features and a target variable.

Input features could be considered as belonging to the following 3 types:

->Objective: factual information;
->Examination: results of medical examination;
->Subjective: information given by the patient.

| Feature Name              | Feature Type        | Data Type          | Description                                                    |
| :------------------------ | :------------------ | :----------------- | :------------------------------------------------------------- |
| **Age** | Objective Feature   | `int` (days)       | Age of the individual in days                                  |
| **Height** | Objective Feature   | `int` (cm)         | Height of the individual in centimeters                        |
| **Weight** | Objective Feature   | `float` (kg)       | Weight of the individual in kilograms                          |
| **Gender** | Objective Feature   | Categorical code   | Gender of the individual                                       |
| **Systolic blood pressure** | Examination Feature | `int`              | Systolic blood pressure                                        |
| **Diastolic blood pressure**| Examination Feature | `int`              | Diastolic blood pressure                                       |
| **Cholesterol** | Examination Feature | Categorical code   | 1: normal, 2: above normal, 3: well above normal               |
| **Glucose** | Examination Feature | Categorical code   | 1: normal, 2: above normal, 3: well above normal               |
| **Smoking** | Subjective Feature  | `binary`           | Indicates if the individual smokes                             |
| **Alcohol intake** | Subjective Feature  | `binary`           | Indicates if the individual consumes alcohol                   |
| **Physical activity** | Subjective Feature  | `binary`           | Indicates if the individual is physically active               |
| **Cardio** | Target Variable     | `binary`           | Presence or absence of cardiovascular disease                  |

# Task
The goal of the project is to analyze Cardiovascular Disease dataset to find which factors are related to the heart diseases.

# Used Tools & Libraries
numpy, pandas, matplotlib, seaborn, sklearn, lightgbm, catboost, pytorch
