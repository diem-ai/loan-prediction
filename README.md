# Loan's Approval Prediction
 - Implement a classification model to predict whether or not a loan application is approved using **Decision Tree Classifier**
 - Explore various techniques for preventing overfitting in decision trees
 - Apply **undersampling** and **ensemble methods (bagging, boosting)** to combat the **imbalanced dataset**
 - Find out the best parameters for each classifier with gridsearch
 - Compare the optimized models with baseline models
 - Evaluate models with accuracy score, precision, recall and F1-score
 
 # Steps
 - Load dataset into pandas dataframe
 - Explore features and select the relavant ones to train model
 - One hot encoding categorical features into numeric 
 - Analysis the proportion of safe and risky loan in dataset
 - **Undersampling** train data/validation data to make sure data is balance, then train **Decision Tree Classifier** (baseline, optimized parameters) and evaluation
 - **Boosting**: The motivation is to combine several weak models to produce a powerful ensemble. Train **Decision Tree Classifier** wrapped in **AdaBoostClassifier** and evaluation
- **Bagging Classifier**: Fit train data to  **Decision Tree Classifier** wrapped in **BaggingClassifier**

# Requirements:
## Softwares:
- Python >= 3.7
- Jupyter Notebook
## Dependencies
- pandas
- numpy
- scikit-learn

# Reference:
Machine Learning Specialization by University of Washington (Cousera)
