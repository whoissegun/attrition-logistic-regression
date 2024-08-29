# Employee Attrition Prediction

This repository focuses on building a logistic regression model to predict employee attrition, determining whether an employee is likely to leave a company based on historical data. The project includes a comprehensive notebook that details the various data visualization, exploration, and preprocessing techniques employed throughout the analysis.

## Key Features

- **Data Visualization**: Utilized various visualization techniques to explore the dataset, uncover key patterns, and identify trends related to employee attrition.
- **Data Exploration**: Conducted thorough examination of the dataset to understand feature distributions, identify potential issues such as missing values, and analyze correlations.
- **Preprocessing**: Implemented data preprocessing steps to prepare the data for modeling, including handling class imbalance and feature engineering.

## Model Evaluation

Given the significant class imbalance in the dataset, where only approximately 16% of the employees left the company, a standard accuracy metric would not provide a meaningful evaluation of the model's performance. To address this, the ROC curve was utilized to determine an optimal decision threshold, allowing for a more realistic assessment of the model through an adjusted accuracy metric.

## Model Performance Metrics

- **Adjusted Accuracy**: 0.66
- **Precision**: 0.27
- **Recall**: 0.66
- **F1 Score**: 0.38

These metrics reflect the challenges posed by the imbalanced dataset, highlighting the trade-offs between precision and recall in the model's predictions.

## Conclusion

This project provides insights into predicting employee attrition using logistic regression. By addressing class imbalance and leveraging ROC curves for optimal threshold selection, the analysis presents a practical approach to improving model performance in real-world scenarios.

