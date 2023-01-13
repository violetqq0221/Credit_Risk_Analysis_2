## Credit Risk Analysis 

##Overview
The purpose of this analysis was to predict the credit risk by following 6 different  machining learning . 
* Random Oversampler with LogisticRegression model
* SMOTE Oversampling with LogisticRegression model
* Clustercentroids resampler with LogisticRegression model
* Smottenn algorithm sampler with LogisticRegression model
* Balanced Random Forest Classifier model
* Easy Ensemble AdaBoost Classifier model

## Result

* Random Oversampler sampler
  * 1. accuracy score: 65.25% 
  * 2. the precision for the high risk is 1% and for high risk 62% sensitivity
  * 3. Recall: High risk/Low risk = 0.62/ 0.68 

  ![fig](https://github.com/violetqq0221/Credit_Risk_Analysis_2/blob/main/Navie_random_oversampling.PNG)
  
  
* SMOTE Oversampling sampler
  * 1. accuracy score: 65.25% 
  * 2. the precision for the high risk is 1% and 69% sensitivity
  * 3. Recall: High risk/Low risk = 0.69/ 0.59

  ![fig](https://github.com/violetqq0221/Credit_Risk_Analysis_2/blob/main/SMOTE.PNG)


* Clustercentroids resampler
  * 1. accuracy score: 63.91% 
  * 2. the precision for the high risk is 1% and 61% sensitivity 
  * 3. Recall: High risk/Low risk = 0.61/ 0.45 

  ![fig](https://github.com/violetqq0221/Credit_Risk_Analysis_2/blob/main/ClusterCentroids.PNG)


* Smottenn algorithm sampling
  * 1. accuracy score: 52.93% 
  * 2. the precision for the high risk is 1% and 70% sensitivity 
  * 3. Recall: High risk/Low risk = 0.70/ 0.57 

  ![fig](https://github.com/violetqq0221/Credit_Risk_Analysis_2/blob/main/SMOTEENN.PNG)


* Balanced Random Forest Classifier model
  * 1. accuracy score: 95.52% 
  * 2. the precision for the high risk is 5% and for high risk 1% sensitivity  
  * 3. Recall: High risk/Low risk = 1/ 0.9 

  ![fig](https://github.com/violetqq0221/Credit_Risk_Analysis_2/blob/main/RandomForestClassifier.PNG)


* Easy Ensemble AdaBoost Classifier model
  * 1. accuracy score: 91.39% 
  * 2. the precision for the high risk is 7% and for high risk 89% sensitivity 
  * 3. Recall: High risk/Low risk = 0.89/ 0.94 

  ![fig](https://github.com/violetqq0221/Credit_Risk_Analysis_2/blob/main/Easy%20Ensemble%20AdaBoost%20Classifier.PNG)


## Summary: 

 This activity we use the following 3 model to train the data
 (1) LogisticRegression
 (2) BalancedRandomForestClassifier
 (3) AdaBoost Classifier
    The first deliver we use four different sampling methonds with Logistic Regression module, the accuracy score 50~65%.
    The Scecond deliver we use Balanced Random Forest Classifier model, the accuracy achive 95.52% also use the Adaboost classifier model,the result is 91.39%. Although adaboost classifier accuracy is not getting better than Random Forset classifier model.Both Random Forest classifier and Adaboost are over 90% better than Logistic Regression with different sampling ways. 
 
 