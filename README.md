# Credit_Risk_Analysis


## Overview: 
The goal of the analysis was to employ different techniques to train and evaluate credit risk models with unbalanced classes. Using imbalanced-learn and scikit-learn libraries I built and evaluated models using a resampling method. 

Using the credit card credit dataset the data was oversampled using the RandomOverSampler and SMOTE algorithms and undersampledusing the ClusterCentroids algorithm. Then a combinatorial approach of over- and undersampling was used using the SMOTEENN algorithm. Finally two machine learning models that reduce bias were compared (BalancedRandomForestClassifier and EasyEnsembleClassifier) to predict credit risk. 

## Results: 

  - Random OverSampling Results: The balanced accuracy is 66%, the precision for the high risk has a positivity of 1% and the recall is 72%.

![Screenshot (214)](https://user-images.githubusercontent.com/90067477/152065693-9b4fe103-89b1-42b0-ae13-42e6fb99cae0.png)

  - SMOTE Oversampling Results: The accuracy is 66%, the precision has a positivity of 1% and he recall is 69%. 

![Screenshot (215)](https://user-images.githubusercontent.com/90067477/152066329-607ee115-9a34-449e-8f04-61df68095186.png)

  - Undersampling Results: The balanced accuracy score is 66%, the precision at 99% and the recall is 40%. 

![Screenshot (216)](https://user-images.githubusercontent.com/90067477/152067060-8a1f0935-7cc4-4d16-ba84-7f55c7817ca3.png)

  - Combination (Over and Under) Sampling Results: The balanced accuracy score is 54%, the precision at 99% and the recall is 57%. 

![Screenshot (217)](https://user-images.githubusercontent.com/90067477/152067261-383b5691-893c-4162-8fb6-ff6eae5bd500.png)

  - Balanced Random Forest Classifier: The balanced accuracy score is 77%, the precision at 99% and the recall is 88%. 

![Screenshot (218)](https://user-images.githubusercontent.com/90067477/152067558-23f9e6ec-2579-488a-947d-c8848fb847b9.png)

  - Easy Ensemble AdaBoost Classifier: The balanced accuracy score is 92%(rounded), the precision at 99% and the recall is 94%.

![Screenshot (219)](https://user-images.githubusercontent.com/90067477/152067819-2f3f5ada-2eca-4f7f-93c4-636759c101ba.png)

## Summary: 
Overall the Easy Ensemble Classifier had the best output of all the classifiers. After over and undersampling the data the results were nowhere near its combination of accuracy, precision and recall. I highly recommend using this model to predict the loan analysis. 
