# Breast-Cancer-CPH
Predicting breast cancer survival using the Cox Proportional-Hazards regression model. Key libraries used include pandas, numpy, matplotlib, seaborn, scikit-learn and lifelines.
Dataset used - Breast Cancer Dataset (https://www.kaggle.com/code/jnegrini/breast-cancer-dataset).


## Notebook Contents
* Initial Data Loading and Profiling - feature definitions and engineering, cleaning and descriptive statistics.
* Exploratory Data Analysis - univariate categorical, continuous variable distributions and correlation matrix.
* Creating the Prediction Model - Cox Proportional-Hazards regression model to predict and explain breast cancer survival time. Includes one-hot encoding, train-test split, grid search and results interpretation.

## Final Model Performance
* Obtained c-index of 0.72 on the test set (typical range 0.55 - 0.75).
