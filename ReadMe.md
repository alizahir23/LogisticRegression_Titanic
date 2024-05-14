# Titanic Survival Analysis

## Overview

This repository hosts a data science project analyzing the survival of passengers aboard the RMS Titanic. The analysis investigates factors influencing survival rates and employs logistic regression to predict outcomes. The dataset used in this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/datasets/yasserh/titanic-dataset).

## Analyses Conducted

### 1. Missing Data Visualization

- **Objective**: Identify missing data in the dataset.
- **Method**: Used a heatmap to visualize missing values.
- **Plot**:

  ![missing_data_heatmap.png](https://i.ibb.co/8m9x2Lk/missing-data-heatmap.png)

### 2. Survival Count by Gender

- **Objective**: Explore the survival count based on gender.
- **Method**: Generated a count plot comparing survival rates between genders.
- **Plot**:

  ![survival_by_gender.png](https://i.ibb.co/c6TGZ7N/survival.png)

  ![enter image description here](https://i.ibb.co/jvLr56Z/survival-by-gender.png)

### 3. Survival Count by Passenger Class

- **Objective**: Analyze how passenger class affects survival rates.
- **Method**: A count plot illustrating survival distribution across different classes.
- **Plot**:

  ![enter image description here](https://i.ibb.co/F75w2RR/survival-by-class.png)

### 4. Age Distribution Among Passengers

- **Objective**: Observe the age distribution of the passengers.
- **Method**: Created a distribution plot for the age variable.
- **Plot**:

![enter image description here](https://i.ibb.co/C2YQmHJ/age-distribution.png)

### 5. Logistic Regression Model

- **Objective**: Predict survival based on variables such as age, sex, passenger class, etc.
- **Method**: A logistic regression model was implemented and trained on the preprocessed data.
- **Results**: The model achieved an accuracy score of 0.797752808988764. Model evaluation details are documented using a confusion matrix.

  ![enter image description here](https://i.ibb.co/RvnH4pM/Screenshot-2024-05-14-at-8-38-24-AM.png)

- **Improvement**: To potentially enhance this model, I will be returning to this project to implement a Gradient Boosting model. Gradient Boosting can provide better performance through ensemble learning techniques that combine multiple weak learning models to create a strong predictive model, potentially improving the accuracy further.

## Installation

Ensure you have Python installed, then set up a virtual environment and install the required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
