# Time-Series-Classification using Logistic Regression
Using Activity Recognition System based on Multisensor Dataset

- Extracted statiscal features from subset of data such as mean, median, min, max, etc.

- Estimated SD using Python's bootstrapped to build a 90% CI for the SD of each feature

- Binary Logistic Regression on a subset (3) of features

  -- Calculated p-values for features, and implemented backward selection/Recursive feature elimination
  
  -- Implemented 5-fold CV (using stratified CV when necessary)
  
  -- Generated ROC Curves for classification results
  
- Binary Logistic Regression using L1 Regularization
  -- Performed CV to determine optimal weight for L1 penalty in model
  
- Multi-Class Logistic Regression using L1 Regularization
  -- Generated confusion matrices
  
- Naive Bayes using L1 Regularization
