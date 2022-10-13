# Credit_Risk_Analysis

## Overview
The purpose of this analysis was to build various machine learning models and evaluate their performance and accuracy at predicting credit risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I have performed a diligent analysis of each machine learning algorithm listed below to apply what I have learned about supervised machine learning thus far and to gain better of understanding of the subject in general.

 * **RandomOverSampler**
 * **SMOTE**
 * **ClusterCentroids**
 * **SMOTEENN**
 * **BalancedRandomForestClassifier**
 * **EasyEnsembleClassifier**
 
## Results
The following results are presented in descending levels of performance, starting with the worst-performing model and moving to the best.

 6. **ClusterCentroids** 

   * Balanced accuracy score: **0.5103** 
   * Recall High/Low risk: **0.59** / **0.43** 

 <img width="1510" alt="cc_as" src="https://user-images.githubusercontent.com/107579508/195461475-ad763795-cf75-4d95-91ba-8d9cffe3a735.png">

 <img width="3110" alt="cc_cm" src="https://user-images.githubusercontent.com/107579508/195461482-87656afc-d53f-4000-84ec-d993d3329274.png">


 5. **SMOTE**

   * Balanced accuracy score: **0.6277** 
   * Recall High/Low risk: **0.62** / **0.63** 

 <img width="1530" alt="smote_as" src="https://user-images.githubusercontent.com/107579508/195461580-62fcfce9-81ad-4e43-afb7-ca4ca7888515.png">

 <img width="3100" alt="smote_cm" src="https://user-images.githubusercontent.com/107579508/195461593-cf4a43b2-499a-43ed-8607-9e3a838b16bd.png">

 4. **RandomOverSampler**

   * Balanced accuracy score: **0.6293** 
   * Recall High/Low risk: **0.57** / **0.68** 

 <img width="1570" alt="ro_as" src="https://user-images.githubusercontent.com/107579508/195461621-aed3749e-98ac-4aaf-8203-73f1769b738a.png">

 <img width="3080" alt="ro_cm" src="https://user-images.githubusercontent.com/107579508/195461625-630c99d5-0800-495e-a73f-87949252ce02.png">

 3. **SMOTEENN**

   * Balanced accuracy score: **0.6411** 
   * Recall High/Low risk: **0.70** / **0.58**  

 <img width="1480" alt="smoteenn_as" src="https://user-images.githubusercontent.com/107579508/195461662-7be37f7a-2c5d-4b3c-96be-124fefe05e61.png">

 <img width="3080" alt="smoteenn_cm" src="https://user-images.githubusercontent.com/107579508/195461667-2f7aa9f3-9da4-4078-8112-2b3c7e9ce584.png">

 2. **BalancedRandomForestClassifier**

   * Balanced accuracy score: **0.7877** 
   * Recall High/Low risk: **0.67** / **0.91**  

 <img width="1460" alt="brfc_as" src="https://user-images.githubusercontent.com/107579508/195461681-d404233a-2867-4c73-98be-5fdc89861ca3.png">

 <img width="3220" alt="brfc_cm" src="https://user-images.githubusercontent.com/107579508/195461687-3b760069-1328-4b7e-a2cf-5847fb9f9e8a.png">

 1. **EasyEnsembleClassifier**

   * Balanced accuracy score: **0.9254** 
   * Recall High/Low risk: **0.91** / **0.94** 

 <img width="1500" alt="eeac_as" src="https://user-images.githubusercontent.com/107579508/195461704-6828c22e-14fc-4b02-be60-d74d8d273016.png">

 <img width="3050" alt="eeac_cm" src="https://user-images.githubusercontent.com/107579508/195461708-2ebfb27c-5cd6-448f-a763-74e0a050767c.png">


## Summary

In conclusion, credit-risk is a difficult thing to predict, even for advanced machine learning algorithms with 95 columns of data to process. While the **EasyEnsembleClassifier** model had the highest overall accuracy, it could be largely due to the fact that the dataset was radically unbalanced. While the **EasyEnsembleClassifier** model had a higher balanced accuracy and average F-score than the other models, its' F-score for high risk prediction was no better than 0.14. 

In the end, I would advise against using any of these algorithms, as they'd put creditors at too great a risk because they could not accurately predict who the high-risk debtors would be.