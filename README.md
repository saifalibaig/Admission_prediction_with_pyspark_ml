# Admission Prediction with PySpark ML

## Overview

This project uses PySpark's machine learning capabilities to predict the chances of admission for students based on their academic profiles and other related factors. The dataset provides insights into the key parameters influencing graduate admissions, making it a valuable resource for aspiring students and academic institutions.

## Features

- **Data Exploration:** Analyze the dataset to understand trends and relationships between variables.
- **Data Preprocessing:** Handle missing values, normalize features, and prepare the data for modeling.
- **Model Building:** Train and evaluate machine learning models using PySpark's MLlib.
- **Feature Importance:** Identify the most influential factors for predicting admission chances.
- **Visualization:** Use Python libraries to generate insights and trends.

## Dataset

The dataset contains the following columns:
- **GRE Score:** GRE test score (out of 340).
- **TOEFL Score:** TOEFL test score (out of 120).
- **University Rating:** Rating of the university (1 to 5).
- **SOP:** Statement of Purpose strength (out of 5).
- **LOR:** Letter of Recommendation strength (out of 5).
- **CGPA:** Undergraduate GPA (on a scale of 10).
- **Research:** Research experience (0 or 1).
- **Chance of Admit:** Probability of admission (0 to 1).

## Technologies Used

- **PySpark:** For large-scale data processing and ML modeling.
- **Python:** For data preprocessing and visualization.

## Project Structure

- `Admission_Predict.csv`: Input dataset.
- `Admission_prediction_with_pyspark_ml.ipynb`: PySpark script for data analysis and prediction.
- `README.md`: Project documentation.

## Steps in the Project

### Data Exploration

- Analyze correlations between features.
- Visualize distributions using Python libraries.

### Data Preprocessing

- Normalize numerical features.

### Model Building and Evaluation

- Split the dataset into training and testing sets.
- Train models like Linear Regression or Decision Trees using PySpark MLlib.
- Evaluate model performance using metrics like RMSE and R².

### Insights

- Highlight key parameters influencing admissions.
  - Example: High GRE scores and CGPA strongly correlate with higher admission chances.

## Results and Insights

- **Finding 1:** GRE scores and CGPA have the highest correlation with admission chances.
- **Finding 2:** Research experience significantly boosts the probability of admission.
- **Finding 3:** University ratings moderately impact admission chances but are less influential than GRE and CGPA.

## Future Enhancements

- Experiment with advanced models such as Random Forest or Gradient Boosting.
- Integrate a web application for interactive admission prediction.
- Add more datasets for a broader analysis.
