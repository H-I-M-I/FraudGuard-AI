# Credit Card Fraud Detection

This project focuses on detecting fraudulent credit card transactions using machine learning models. It employs both Support Vector Machine (SVM) and Decision Tree classifiers to identify fraudulent activities efficiently. The implementation leverages Scikit-Learn and Snap ML for training and evaluation.

## Dataset

The dataset used in this project is the Credit Card Fraud Detection dataset from Kaggle. It contains anonymized transaction details with labeled instances of fraud and non-fraud.

## Features

- **Data Preprocessing**: Normalization and standardization of transaction data.
- **Model Training**: Implementation of **SVM** and **Decision Tree** classifiers.
- **Performance Evaluation**: Measuring model performance using **ROC-AUC Score**.

## Implementation Details

### **Scikit-Learn Usage:**
1. **Data Preprocessing**  
   - `StandardScaler` is used for **feature scaling**.
   - `train_test_split` is used to **split the dataset** into training and test sets.

2. **Model Training**  
   - `SVC()` (Support Vector Classifier) from `Scikit-Learn` is used to train an SVM model.
   - `DecisionTreeClassifier()` is used to train a Decision Tree model.

3. **Evaluation**  
   - `roc_auc_score` is used to measure the **ROC-AUC Score** for model performance.

### **Snap ML Usage:**
1. **Optimized Training**  
   - Snap ML provides an optimized version of **SVM** for faster model training.
   - The library improves computational efficiency, making training faster compared to standard Scikit-Learn implementations.

## Results
The trained models are evaluated based on their ability to distinguish fraudulent transactions. The ROC-AUC score is used as the primary metric.


### Contact

- **LinkedIn**: [https://linkedin.com/in/himi02](https://linkedin.com/in/himi02)
- **Email**: [[your\_email@example.com](mailto:your_email@example.com)]

