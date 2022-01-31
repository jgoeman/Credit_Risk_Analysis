# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to provide models to prefict credit risk.Credit risk is an inherently unbalanced classification problem as good loans easily outnumber risky loans. Therefore we will use a few different algorythms to see which machine learning model works best to predict credit risk. The following methods were used in this process:
- RandomOverSampler
- SMOTE
- ClusterCentroids
- SMOTEENN
- BalancedRandomForestClassifier
- EasyEnsembleClassifier    

    
Data was taken from a credit card credit dataset from LendingClub, a peer-topeer lending services company and provided as a csv file. Once the file was cleaned there were 68,817 rows and 95 columns of usable data. 

## Results
The following results were obtained for each technique used to train eand evaluate the models:
- RandomOnverSampler
  1. Balanced Accuracy: 63.47%
  2. Precision and Recall:    
  ![image](https://user-images.githubusercontent.com/36859475/151735210-7c3273f7-3d59-444e-8abe-9f173dd226ed.png)
  
- SMOTE
  1. Balanced Accuracy: 66.21%
  2. Precision and Recall:    
  ![image](https://user-images.githubusercontent.com/36859475/151735333-8dfb73d6-e89f-49b0-8ed9-2b73145f634e.png)
  
- ClusterCentroids
  1. Balanced Accuracy: 54.47%
  2. Precision and Recall:   
  ![image](https://user-images.githubusercontent.com/36859475/151735363-cd2bc7ee-273f-4c88-af5b-7410617646b7.png)
 
- SMOTEENN
  1. Balanced Accuracy: 64.47%
  2. Precision and Recall:    
  ![image](https://user-images.githubusercontent.com/36859475/151735406-50e4e1bc-6991-40dc-befb-01faf07ca8fd.png)

- BalancedRandomForestClassifier
  1. Balanced Accuracy: 78.57%
  2. Precision and Recall:    
  ![image](https://user-images.githubusercontent.com/36859475/151735443-41c78362-5e39-4dec-8846-b4802a698788.png)

- EasyEnsembleClassifier
  1. Balanced Accuracy: 93.29%
  2. Precision and Recall:    
  ![image](https://user-images.githubusercontent.com/36859475/151735457-94d921b7-bc87-4202-8787-b9c564fa08c0.png)

## Summary
