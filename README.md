# paircoding-eda-fraud-detection

Dataset
- **Source:** [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- 
## 🔍 EDA Summary
### Key Findings
1. **Missing Values:** No missing data found in the dataset.  
2. **Class Imbalance:**  
   - Non-fraudulent transactions: 99.83%  
   - Fraudulent transactions: 0.17%  
   This extreme imbalance must be addressed before model training.  
3. **Visualization:**  
   - Count plot clearly shows imbalance between fraud and non-fraud classes.  
   - Log scale used for better visibility of minority class.

## 🔄 Future Work
- Conduct correlation and feature distribution analysis.  
- Perform outlier detection and scaling.  
- Apply PCA for feature reduction and visualization.  
- Handle data imbalance (e.g., SMOTE or undersampling).  
- Build machine learning models to classify fraudulent transactions.
