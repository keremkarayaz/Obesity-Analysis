# Obesity Analysis and Prediction Using Machine Learning

This repository contains a comprehensive analysis of obesity-related data, including data preprocessing, exploratory data analysis, and predictive modeling using machine learning techniques. The goal is to identify patterns and build a robust model to predict obesity levels based on lifestyle, dietary, and physical factors.

## Objectives

This project seeks to:
1. Understand the impact of various lifestyle choices and demographic factors on obesity.
2. Visualize the distribution of obesity levels across different groups (e.g., age, gender).
3. Build and evaluate machine learning models to predict obesity levels with high accuracy.
4. Provide actionable insights to support healthier lifestyle choices.

## Dataset Description

The dataset includes several key features that influence obesity levels:
- **Age**: The age of the individual.
- **Gender**: Male or Female.
- **Height and Weight**: Metrics used to calculate BMI (Body Mass Index).
- **Dietary Habits**: Information on fast food consumption, daily meal patterns, and other eating behaviors.
- **Physical Activity**: Frequency and intensity of physical exercise.
- **Obesity Level**: The dependent variable, categorizing individuals into different obesity levels (Underweight, Normal, Overweight, Obese).

## Steps and Methodology

### 1. **Data Preprocessing**
- Cleaned the dataset by handling missing values and anomalies.
- Normalized and scaled numeric data.
- Encoded categorical variables for machine learning compatibility.

### 2. **Exploratory Data Analysis (EDA)**
- Analyzed BMI distributions and obesity levels across age groups and genders.
- Visualized relationships between physical activity, dietary habits, and obesity levels.
- Explored correlation matrices to identify significant relationships between variables.

### 3. **Feature Engineering**
- Calculated BMI using height and weight data.
- Created new features based on combined dietary and physical activity patterns.

### 4. **Machine Learning Modeling**
- Applied multiple classification algorithms:
  - Logistic Regression
  - Decision Tree Classifier
  - Random Forest Classifier
  - Gradient Boosting Classifier
- Performed hyperparameter tuning to optimize model performance.
- Evaluated models using metrics such as accuracy, precision, recall, and F1-score.

### 5. **Visualization and Insights**
- Created bar plots, scatter plots, and heatmaps to communicate findings.
- Highlighted the most significant factors influencing obesity.

## Key Findings

1. **Physical Activity Matters**: Lack of regular exercise is strongly correlated with higher obesity levels.
2. **Dietary Patterns Influence Obesity**: Frequent consumption of fast food and irregular meals contribute to weight gain.
3. **Age and Gender Trends**: Obesity levels tend to increase with age, and males/females exhibit different patterns based on lifestyle.
4. **Model Performance**: The Random Forest Classifier outperformed other models, achieving the highest accuracy.

## Requirements

Python 3.7+
Libraries:
pandas: For data manipulation.
numpy: For numerical computations.
matplotlib and seaborn: For data visualization.
scikit-learn: For building and evaluating machine learning models.

## Visualization Highlights

Distribution of obesity levels visualized with histograms and pie charts.
Correlation heatmaps to identify relationships between features.
Feature importance plots to highlight the most influential factors in predicting obesity.

## Potential Applications

Health and Wellness Apps: Integrate findings into apps to provide personalized health recommendations.
Public Health Campaigns: Use insights to target groups at higher risk of obesity.
Predictive Healthcare: Early identification of obesity risk to prevent associated health issues.

## Contributing

Contributions are always welcome! If you have ideas to improve the analysis or add new features, feel free to:

Fork this repository.
Make your changes.
Submit a pull request with a description of the improvements.

## License 

This project is licensed under the MIT License. For more details, refer to the LICENSE file.



