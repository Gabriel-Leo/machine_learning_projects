# Binary Classification: Diabetes Prediction

This project explores a binary classification problem using machine learning models to predict whether a patient is diabetic or non-diabetic based on medical measurements.

The notebook includes:
- Data cleaning and preprocessing
- Missing value handling with KNN imputation
- Outlier detection using the IQR method
- Feature scaling and log transformations
- Hyperparameter tuning with GridSearchCV
- Model evaluation using accuracy and recall metrics

## Models Used

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest Classifier

## Project Goal

Since missing diabetic patients can have serious consequences, recall was considered the most important evaluation metric.
Among the evaluated models, the Random Forest classifier achieved the best recall performance on the test dataset.

## Technologies Used

- Python 3.13.5
- NumPy 2.3.1
- Pandas 2.3.2
- Scikit-learn 1.7.1
- SciPy 1.16.0
- Matplotlib 3.10.5