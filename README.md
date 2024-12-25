# Credit Card Fraud Detection

## Objective
The goal of this project is to develop a machine learning model to detect fraudulent credit card transactions. The dataset contains transaction records with features indicating the details of each transaction, and the task is to classify each transaction as either fraudulent or genuine.

## Approach
### 1. **Data Preprocessing**
- **Normalization:** Scaled features to bring them into a comparable range.
- **Handling Class Imbalance:** Applied techniques like oversampling (SMOTE) to address the skewed distribution between fraudulent and non-fraudulent transactions.
- **Feature Engineering:** Retained and utilized relevant features based on domain understanding and exploratory data analysis.

### 2. **Model Development**
- Explored multiple classification algorithms such as:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting (e.g., XGBoost)
- Evaluated models using metrics including:
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC

### 3. **Evaluation**
- **Metrics:** Focused on recall and F1-score to prioritize minimizing false negatives while maintaining a balance with false positives.
- **Validation:** Performed train-test split and cross-validation for robust model assessment.

## Results
The final model achieved:
- **Precision:** 100%
- **Recall:** 100%
- **F1-Score:** 100%
- **ROC-AUC:** 99.99%


## Challenges
- **Class Imbalance:** Addressing the disparity between fraudulent and non-fraudulent transactions without overfitting.
- **Data Confidentiality:** Ensuring no sensitive information from the dataset is exposed in visualizations or code.

## Conclusion
The project successfully demonstrated the application of machine learning techniques to detect credit card fraud with a focus on mitigating class imbalance and maximizing evaluation metrics. The developed model can be further optimized for deployment in real-world systems.

## Repository Structure
```
├── data
│   ├── creditcard.csv  # Dataset used for this project
├── notebooks
│   ├── Task_5_Credit_Card_Fraud_Detection.ipynb  # Jupyter Notebook with the full code
├── models
│   ├── fraud_detection_model.pkl  # Saved Random Forest model
├── README.md  # Project documentation
```

## References
- [Credit Card Fraud Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Concepts from [Scikit-learn documentation](https://scikit-learn.org/stable/).

---
