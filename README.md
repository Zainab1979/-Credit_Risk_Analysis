# -Credit_Risk_Analysis
## Overview of the loan prediction risk analysis:
In this project we use machine learning to predect the risk of cridet card base on 85 features .
We classify the crited card risk to high risk or low risk.
Our main challenge in this proplem is the inpalance data as high risk intances are very low coper to low risl instances.
We experiment with six diffrent mechine learning models to overcame the imbalance problem.
We present the results of each model in this file.
## Results:
* The screen shows below shows the results of oversampling:
![Over_sampling](https://github.com/Zainab1979/-Credit_Risk_Analysis/blob/36c262d366ef3247730baf00c5ae07cb84152996/over%20sampling.png) <br> 
* The screen shows below shows the results of smote:
![smote](https://github.com/Zainab1979/-Credit_Risk_Analysis/blob/36c262d366ef3247730baf00c5ae07cb84152996/smote.png) <br> 
* The screen shows below shows the results of undersampling:
![undersampling](https://github.com/Zainab1979/-Credit_Risk_Analysis/blob/36c262d366ef3247730baf00c5ae07cb84152996/undersambling.png) <br> 
* The screen shows below shows the results of combination:
![combination](https://github.com/Zainab1979/-Credit_Risk_Analysis/blob/36c262d366ef3247730baf00c5ae07cb84152996/combination.png) <br> 
* The screen shows below shows the results of Balanced Random Forest :
![BRF](https://github.com/Zainab1979/-Credit_Risk_Analysis/blob/36c262d366ef3247730baf00c5ae07cb84152996/BRF.png) <br> 
* The screen shows below shows the results of Easy Ensemble AdaBoost Classifier:
![Ada](https://github.com/Zainab1979/-Credit_Risk_Analysis/blob/36c262d366ef3247730baf00c5ae07cb84152996/Ada.png) <br> 
## Summary:
From the above screen shots of model accuracy, Easy Ensemble AdaBoost Classifier with accuracy score 0.93.
Where as the other models was giving less accuracy.hence Easy Ensemble AdaBoost Classifier is best model for given data.
Balanced Random Forest was giving an accuracy score of 0.78 followed by SMOTE Oversampled logistic regression with score of 0.66,Naive Random Oversampling with score 0.64 and others with even lower score.
So we recommend to use our Easy Ensemble AdaBoost Classifier.

