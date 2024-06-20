# Obesity Prediction with Machine Learning and Hyperparameter Tuning

## Project Description

This project aims to predict obesity status using a variety of machine learning algorithms. The dataset utilized in this project is the 'ObesityDataSet_raw_and_data_sinthetic.csv', which includes various features related to individual health and lifestyle.

## Project Steps

1. **Data Loading and Exploration**:
   - Loaded the dataset and performed initial exploration to understand the structure and contents.
   - Conducted data profiling to summarize the main characteristics of the data.

2. **Data Preprocessing**:
   - Encoded categorical variables for machine learning model compatibility.
   - Split the data into feature matrix (X) and target vector (y).
   - Standardized the feature matrix to normalize the data.

3. **Train-Test Split**:
   - Split the dataset into training (80%) and testing (20%) sets to evaluate model performance.

4. **Model Training and Evaluation**:
   - Implemented multiple classification algorithms:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - Decision Tree
     - Random Forest
     - Gradient Boosting Classifier

   - Evaluated each model's performance using accuracy, precision, recall, F1-score, and confusion matrix.
   - Identified Gradient Boosting Classifier as the best-performing model.

5. **Hyperparameter Tuning**:
   - Performed hyperparameter tuning on the Gradient Boosting Classifier using GridSearchCV to optimize its performance.
   - Evaluated the tuned model's performance to ensure improvement.

## Results

- **Logistic Regression**: Accuracy - 86.60%
- **K-Nearest Neighbors**: Accuracy - 80.38%
- **Support Vector Machine**: Accuracy - 88.52%
- **Decision Tree**: Accuracy - 91.87%
- **Random Forest**: Accuracy - 95.22%
- **Gradient Boosting**: Accuracy - 95.45%

The Gradient Boosting Classifier, after hyperparameter tuning, achieved the highest accuracy and proved to be the most effective model for predicting obesity status.

## Conclusion

This project demonstrates a comprehensive approach to predicting obesity status using various machine learning algorithms and optimizing the best model through hyperparameter tuning. The results highlight the importance of model selection and tuning in achieving high predictive accuracy.
