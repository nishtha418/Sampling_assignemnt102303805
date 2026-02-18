#Sampling Techniques on Imbalanced Dataset
-> Objective:
The objective of this experiment is to study the impact of different sampling techniques on machine learning model performance when working with an imbalanced dataset.

->Dataset:
The Credit Card Fraud dataset contains transactions labeled as fraudulent and non-fraudulent. The dataset is highly imbalanced because fraudulent transactions are very few compared to normal transactions.

->Methodology:
To handle the imbalance problem, five sampling techniques were applied:
Random Over Sampling
SMOTE (Synthetic Minority Over-sampling Technique)
NearMiss
SMOTEENN
SMOTETomek

Each sampling technique was used to balance the dataset and then five machine learning models were trained and evaluated:
Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)

The dataset was split into training and testing sets and accuracy was used as the evaluation metric.

->Result:
The results showed that model performance varies significantly depending on the sampling method used. Oversampling techniques such as SMOTE and hybrid methods (SMOTEENN, SMOTETomek) generally improved classification accuracy compared to simple undersampling methods.

Random Forest achieved the best performance among all models on balanced datasets.

Conclusion

Sampling techniques play a very important role in handling imbalanced datasets. Proper balancing of data improves the learning capability of machine learning models and results in better classification accuracy.
