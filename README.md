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
The following results are presented in ascending levels of performance, starting with the worst-performing model and moving to the best.

 * **ClusterCentroids**

 <img width="151" alt="cc_as" src="https://user-images.githubusercontent.com/107579508/195461475-ad763795-cf75-4d95-91ba-8d9cffe3a735.png">

 <img width="311" alt="cc_cm" src="https://user-images.githubusercontent.com/107579508/195461482-87656afc-d53f-4000-84ec-d993d3329274.png">


 * **SMOTE**

 <img width="153" alt="smote_as" src="https://user-images.githubusercontent.com/107579508/195461580-62fcfce9-81ad-4e43-afb7-ca4ca7888515.png">

 <img width="310" alt="smote_cm" src="https://user-images.githubusercontent.com/107579508/195461593-cf4a43b2-499a-43ed-8607-9e3a838b16bd.png">

 * **RandomOverSampler**

 <img width="157" alt="ro_as" src="https://user-images.githubusercontent.com/107579508/195461621-aed3749e-98ac-4aaf-8203-73f1769b738a.png">

 <img width="308" alt="ro_cm" src="https://user-images.githubusercontent.com/107579508/195461625-630c99d5-0800-495e-a73f-87949252ce02.png">

 * **SMOTEENN**

 <img width="148" alt="smoteenn_as" src="https://user-images.githubusercontent.com/107579508/195461662-7be37f7a-2c5d-4b3c-96be-124fefe05e61.png">

 <img width="308" alt="smoteenn_cm" src="https://user-images.githubusercontent.com/107579508/195461667-2f7aa9f3-9da4-4078-8112-2b3c7e9ce584.png">

 * **BalancedRandomForestClassifier**

 <img width="146" alt="brfc_as" src="https://user-images.githubusercontent.com/107579508/195461681-d404233a-2867-4c73-98be-5fdc89861ca3.png">

 <img width="322" alt="brfc_cm" src="https://user-images.githubusercontent.com/107579508/195461687-3b760069-1328-4b7e-a2cf-5847fb9f9e8a.png">

 * **EasyEnsembleClassifier**

 <img width="150" alt="eeac_as" src="https://user-images.githubusercontent.com/107579508/195461704-6828c22e-14fc-4b02-be60-d74d8d273016.png">

 <img width="305" alt="eeac_cm" src="https://user-images.githubusercontent.com/107579508/195461708-2ebfb27c-5cd6-448f-a763-74e0a050767c.png">


## Summary

