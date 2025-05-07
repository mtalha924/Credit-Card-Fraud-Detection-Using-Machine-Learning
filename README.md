# Credit-Card-Fraud-Detection-Using-Machine-Learning

A machine learning system to detect fraudulent credit card transactions using Random Forest classifier with SMOTE for handling class imbalance.

## Features

- Handles highly imbalanced dataset (typical fraud detection scenario)
- Uses SMOTE (Synthetic Minority Over-sampling Technique) for balancing classes
- Random Forest classifier with optimized hyperparameters
- Comprehensive evaluation metrics:
  - Precision, Recall, F1-Score
  - Confusion Matrix
- Interactive command-line testing interface
- Model persistence using joblib

## Installation
Install the required packages
- `pip install -r requirements.txt`
- `pip install tensorflow scikit-learn streamlit pandas numpy imbalanced-learn matplotlib seaborn joblib`

## Streamlit Deployment
- Create `app.py` for Streamlit deployment
- Run `streamlit run app.py` to execute the code
- Access the web interface at `http://localhost:8501/`

## Dataset
- The system uses the dataset from Kaggle which can be accessed here `https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud`
- The dataset contains 284,807 transactions, 492 frauds (0.172% of all transactions), 30 features (28 anonymized principal components + Amount + Time)

## Model Performance
| Metric     | Score  |
|------------|--------|
| Precision  | 0.9994 |
| Recall     | 0.9992 |
| F1-Score   | 0.9993 |


  
