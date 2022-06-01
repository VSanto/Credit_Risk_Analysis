# Credit_Risk_Analysis

#### Overview of the loan prediction risk analysis:

The purpose of this analysis was to evaluate three machine learning models by using resampling to determine which is better at predicting credit risk.

## Results: 

### OverSampling:

 ####   Naive Random Oversampling
      *  High Risk = 51352
      *  Low Risk = 51352
      *  Balanced Accuracy Score = 64% 
      
![Naive Random Oversampling Imbalanced  Classification Report](https://user-images.githubusercontent.com/92495807/171337759-a6cb8a2a-b427-4d6f-a685-81e2d14bf83c.PNG)

  ####   SMOTE Oversampling
      *  High Risk = 51352
      *  Low Risk = 51352
      *  Balanced Accuracy Score = 63%  

![SMOTE Oversampling Imbalanced  Classification Report](https://user-images.githubusercontent.com/92495807/171338379-cda1d700-f15d-4754-b69f-fb8370f75a12.PNG)

### UnderSampling:

####   ClusterCentroids
      *  High Risk = 260
      *  Low Risk = 260
      *  Balanced Accuracy Score = 63%
      
![ClusterCentroids Imbalanced  Classification Report](https://user-images.githubusercontent.com/92495807/171338980-c38cd76e-6690-49f8-93c7-cac833dea878.PNG)

### Combination Over Under Sampling

####   SMOOTEENN
      *  High Risk = 68460
      *  Low Risk = 6201
      *  Balanced Accuracy Score = 51%
      
![SMOOTEENN Imbalanced  Classification Report](https://user-images.githubusercontent.com/92495807/171339407-9e39277c-99e8-4bcf-8a16-be7b318003bd.PNG)

#### Balanced Random Forest Classifier
      *  High Risk = 
      *  Low Risk = 
      *  Balanced Accuracy Score = 78%
      
![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/92495807/171340040-5707de78-03e2-40ec-86d3-511a5e089ee7.PNG)

#### Easy Ensemble AdaBoost Classifier
      *  High Risk = 
      *  Low Risk = 
      *  Balanced Accuracy Score = 93%

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/92495807/171340301-15557e08-da90-4273-9f1b-d14e8fc6ec05.PNG)

## Summary:

The oversampling models, both had high and low risk the exact same amount, with accuracy in the 60s.
The undersampling model also had the same high low risk, and also, with accuracy in the 60s.
The Smootheenn has high risk at 68460 and low risk at 6201, with the lowest accuracy in the 50s.
The Balanced Random Forest Classifier has accuracy in the high 70s.  I believe high risk is upper 80s-90s with low risk in the 60s
Easy Ensemble AdaBoost Classifier has an accuracy score of 93%.  The high risk is in the 90s and the low risk is in high 80s.

I would recommend trying more with the Balanced Random Forest Classifier.  With a few adjustments the model may predict credit risk accurately.
