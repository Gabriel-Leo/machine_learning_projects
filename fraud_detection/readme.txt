# Imbalanced Data Classification: Fraud Detection

This project explores machine learning techniques for detecting fraudulent financial transactions in an imbalanced dataset. The notebook focuses on preprocessing strategies, class imbalance handling, model optimization, and evaluation using metrics more appropriate for fraud detection tasks.

Two ensemble-based classification models were trained and evaluated to identify fraudulent transactions while minimizing the impact of class imbalance.

## Models Used

- Random Forest Classifier
- HistGradientBoostingClassifier

## Project Features

- Train/test split with stratified sampling
- Random undersampling of the training dataset
- RobustScaler preprocessing for outlier-resistant scaling
- Hyperparameter tuning using GridSearchCV
- Evaluation using F1-score and recall metrics
- Correlation analysis and exploratory data visualization

## Evaluation Strategy

Because fraud detection datasets are highly imbalanced, accuracy was not considered a reliable metric. Instead, F1-score was selected as the primary evaluation metric because it balances both precision and recall. Recall was also monitored due to the importance of correctly identifying fraudulent transactions.

## Notes About the Dataset

The unusually high model performance may be influenced by the characteristics of the dataset itself. The dataset appears to be synthetic or highly engineered, potentially containing:
- artificially separable patterns
- engineered fraud signatures
- simplified feature distributions


## Technologies Used

- Python 3.13.5
- Pandas 2.3.2
- Scikit-learn 1.7.1
- SciPy 1.16.0
- Matplotlib 3.10.5
- Seaborn 0.13.2
- imbalanced-learn 0.14.0