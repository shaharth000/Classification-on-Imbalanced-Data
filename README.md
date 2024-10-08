# Classification-on-Imbalanced-Data Using Machine Learning

This project aims to predict insurance claims using machine learning techniques, focusing on handling imbalanced data. The dataset consists of 58,592 entries with 41 features, where the target variable `claim_status` indicates whether a claim was made (1) or not (0). The project leverages various resampling techniques to address the imbalance in the target variable and build effective classification models.

## Key Steps

**Exploratory Data Analysis (EDA):** Conducted EDA on both numerical and categorical features to understand their distributions and relationships with the target variable.

**Handling Imbalanced Data:** Applied resampling techniques from sklearn to balance the dataset, including oversampling and undersampling strategies.

**Feature Importance:** Carried out feature importance analysis to identify the most significant features influencing the prediction of claims.

**Modeling:** Used a Random Forest model on both the original dataset and the oversampled data to assess model performance.


## Tools and Libraries

**Python**
pandas, numpy for data manipulation
matplotlib, seaborn for data visualization
scikit-learn for resampling techniques and machine learning algorithms
