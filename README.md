# Salary Prediction using Naive Bayes

## Project Overview

This project applies a Naive Bayes classification model to predict an individual's salary based on various features such as age, education, occupation, marital status, and more. The model is trained and tested using the `MultinomialNB` algorithm, and the accuracy of the model is evaluated using training and test datasets.

## Dataset Description

The dataset contains the following features:
- **Age**: Age of the individual
- **Workclass**: Type of work (e.g., private, government)
- **Education**: Education level (e.g., Bachelor's, Master's)
- **Marital Status**: Marital status of the individual (e.g., married, divorced)
- **Occupation**: Job type (e.g., tech, healthcare)
- **Relationship**: Relationship status (e.g., husband, wife)
- **Race**: Race of the individual (e.g., White, Black)
- **Sex**: Gender of the individual (e.g., male, female)
- **Capital Gain**: Profit from investment
- **Capital Loss**: Loss from investment
- **Hours per Week**: Number of working hours per week
- **Native**: Native country
- **Salary**: Predicted salary category (e.g., >50K, <=50K)

## Requirements

- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib` (for visualization, if needed)

## Installation

```bash
pip install pandas numpy scikit-learn matplotlib
```

## Approach

1. **Data Preprocessing**:
   - Clean the data by handling missing values and encoding categorical variables.
   - Split the dataset into training and testing sets.

2. **Modeling**:
   - Use `MultinomialNB` from scikit-learn to train the Naive Bayes model.

3. **Evaluation**:
   - Evaluate model performance using accuracy score on training and test datasets.

## Results

- **Training accuracy score**: 0.77
- **Test accuracy score**: 0.77

## Conclusion

The Naive Bayes classifier performed well with an accuracy of 77% on both the training and test datasets. This indicates that the model can predict an individual's salary category based on the given features with reasonable accuracy.
