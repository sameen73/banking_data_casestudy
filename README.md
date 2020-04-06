# banking_data_casestudy
Repository for all files associated with the banking data case study.

**Purpose:** A banking institution seeks to predict client subscription to a term deposit product via a direct marketing campaign (phone calls). 

**Data:** The data comes from the UCI Machine Learning Repository and is based on real data from a Portuguese banking institution. The repository offers four different versions of the data. I opted for the smaller version with more features (4119 observations and 20 features). This particular dataset has records from May 2008 to November 2010. 

**Approach:** This problem is a classification problem. Noting the imbalance between the target classes, I opted to use the Area under the Precision-Recall Curve as the metric for model evaluation. I tried and tuned 4 different machine learning models: logistic regression, XGBoost, random forest, and support vector machine. Ultimately, the XGBoost performed best on test data, but *all models exhibited a strong tendency to overfit the training*. 
