# Heart-Disease-Prediction
(Binary classification using Random Forest classifier by implementing the Data Balancing Techniques.)

In this model I have tried to use Random Forest Classifier for prediction of heart disease. Since there are more than 90% entries with No Heart Disease and only 10% with heart Disease, there is huge unbalance in data and model was tending to predict all the test cases as yes resulting in biased results. Althogh the data was biased the accuracy was around 91% but with poor recall as there were almost no predictions with heart disease.
In order to get unbiased model I've used 2 data balancing techniques Random Under-sampling and Synthetic Minority Oversampling Technique (SMOTE). 

Results:
SMOTE turned out to better balancing technique with Better recall and accuracy compared to Random Undersampling.
 SMOTE Accuracy- 82% ; Precision- 80%;   Recall- 86%
 Random Under-sampling Accuracy- 76% ; Precision-73% ; Recall - 80%
 

