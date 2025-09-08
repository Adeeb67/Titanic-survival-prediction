# Titanic Survival Prediction

## Project Overview
This project predicts passenger survival on the Titanic using Logistic Regression. It demonstrates a complete data analysis and machine learning workflow, including data cleaning, feature engineering, model training, evaluation, and visualization of results.  

The project provides insights into which factors influenced survival and showcases practical data analysis skills suitable for data analyst or junior data science roles.

---

## Dataset
The Titanic dataset contains information about passengers, including:  
- Passenger demographics (Age, Sex)  
- Travel details (Pclass, Fare, Embarked, SibSp, Parch)  
- Survival status (target variable: Survived)  

The dataset is publicly available on Kaggle and commonly used for beginner ML projects.  

---

## Project Workflow

### 1. Data Loading
- Loaded the dataset and previewed the first few rows to understand its structure.

### 2. Data Exploration
- Examined data types, missing values, and summary statistics.  
- Identified columns with missing values and potential irrelevant features.

### 3. Data Cleaning
- Filled missing Age and Fare values with their median.  
- Filled missing Embarked values with the mode.  
- Dropped irrelevant columns like PassengerId, Name, Ticket, and Cabin.  

### 4. Feature Encoding
- Converted categorical features to numeric:  
  - Sex: male → 0, female → 1  
  - Embarked: one-hot encoded  

### 7. Model Training
- Trained a Logistic Regression model on the training set.  
- Made predictions on the test set.

### 8. Model Evaluation
- Evaluated performance using:  
  - Accuracy  
  - Confusion Matrix  
 
### 9. Visualization
- Confusion Matrix Heatmap: showed correct vs incorrect predictions.  
- Feature Importance: highlighted which features influenced survival the most.  
- Survival Analysis: visualized survival patterns by gender and class.

## Insights & Observations
- Females had a higher survival rate than males.  
- First-class passengers survived more often than second or third class.
- 
## Challenges Faced
- Missing values in Age, Fare, and Embarked initially caused errors during modeling.  
- Non-numeric data like Name, Ticket, and Cabin needed to be dropped or encoded.  
- Persistent NaN values required multiple checks and imputation steps.  
- Categorical features needed proper encoding for Logistic Regression.  
- Iterative data cleaning and feature engineering were necessary for dataset completeness and model performance.

## Conclusion
- This project demonstrates a complete data analysis and machine learning workflow.  
- Key features influencing survival: Sex, Pclass, Age and Fare.  
- Combining modeling with visualization provided both predictive insights and interpretability.  
- Proper handling of missing values, feature encoding, and engineering were critical for model success.

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (Logistic Regression, train-test split, metrics)  

## Future Improvements
- Experiment with other models like Random Forest or Gradient Boosting for potentially higher accuracy.  
- Perform hyperparameter tuning to optimize model performance.  
- Include additional exploratory data analysis to extract deeper insights.

