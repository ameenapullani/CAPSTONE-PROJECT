# CAPSTONE-PROJECT

Random Forest Classifier for Loan Prediction.
This project demonstrates the use of a Random Forest Classifier to solve Loan prediction. The model was fine-tuned using hyperparameter tuning methods like GridSearchCV to achieve optimal performance, reaching an accuracy of 96.40%. The project also includes feature selection using filter, wrapper, and embedded methods to improve the model’s efficiency.

# Key Features:
Model comparison: Evaluated several machine learning algorithms including Logistic Regression, SVM, MLP, Random Forest, and Gradient Boosting.
Feature selection: Applied multiple feature selection techniques to identify the most important predictors.
Hyperparameter Tuning: Used GridSearchCV for optimal hyperparameters with 5-fold cross-validation.
ROC Curve: Achieved an AUC score of 0.9979, indicating excellent classification performance.
# Technologies Used:
Python (Scikit-learn, Pandas, Matplotlib)
Collab Notebook
# Results:
Best Model: Random Forest with 96.40% accuracy, precision, and F1-score of 96%+.
Best Hyperparameters: {'bootstrap': False, 'max_depth': 30, 'max_features': 'sqrt', 'min_samples_leaf': 2, 'min_samples_split': 5, 'n_estimators': 200}
