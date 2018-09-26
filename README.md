# Cardiac-Arrhythmia-Classification

What I've learned from this classification problem:
1. Missing values imputation: Know when I should drop an observation with missing values vs. when to impute missing values.
2. Learn different classification models: KNN Classfication, Logistics Regression, SVM, Decision Tree, Random Forest
3. Compare and recognize the effect of feature selection upon training models
4. In a healthcare problem, when the negative diagnosis is much more popular than a positivve diagnosis, we need to look beyond R-square, MSE to evaluate the model. 
In this problem, there is 1 negative diagnosis and 16 positive diagnoses, so that I include accuracy, accuracy_positive (treat all 16 positive diagnoses as 1 positive diagnosis)
and true_postitive for model comparison.