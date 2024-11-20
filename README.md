# Flight-Delays-A-Random-Forest-Model

The following project is about applying a Random Forest Classifier to a dataset sample of flights to New York during 2014. I used this dataset during my master´s degree in Big Data and Business Analytics. While the project´s idea was to prove that we correctly acquired the knowledge to apply machine learning models, the results were far from desired. The goal now is to create a model that predicts delayed flights correctly.

To classify flights with important delays we created the variable "important_delay", for flights with a delay over 60 minutes. This classification comes with the problem of class imbalance. The flights with more than 60 minutes delay represent a minority of the dataset. For such reasons, I decided to implement oversampling techniques (SMOTE & ADASYN) to balance the minority class to the majority class. 

After applying oversampling techniques, I built the Random Forest Classifier with different variables, applied to both datasets. Then, I evaluated the models and the feature importance to extract meaningful conclusions.
