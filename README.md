# Credit_Risk_Analysis

# Overview of the analysis:
Jill has really likee the work we have done and now ready to put us to work on the real world challenge: credit card risk

# Resuilts:
* Naive Random Oversampling:
  * Precision:
    * High_risk: 0.00
    * Low_Risk: 0.99  
  * Recall: 
    * High_risk: 0.00
    * Low_Risk: .99
* SMOTE :
  * Precision:
    * High_risk: 0.00
    * Low_Risk: 0.99  
  * Recall: 
    * High_risk: 0.00
    * Low_Risk: 1.00
* Undersampling :
  * Precision:
    * High_risk: 0.01
    * Low_Risk: 1.00 
  * Recall: 
    * High_risk: 0.67
    * Low_Risk: 0.43
* Combination(Over and Under) Sampling :
  * Precision:
    * High_risk: 0.01
    * Low_Risk: 1.00 
  * Recall: 
    * High_risk: 0.74
    * Low_Risk: 0.57
* Balanced Random Forest Classifier:
  * Precision:
    * High_risk: 0.03
    * Low_Risk: 1.00 
  * Recall: 
    * High_risk: 0.68
    * Low_Risk: 0.87
* Easy Ensemble AdaBoost Classifier:
  * Precision:
    * High_risk: 0.09
    * Low_Risk: 1.00 
  * Recall: 
    * High_risk: 0.92
    * Low_Risk: 0.94
# Summary: 
Now first off right off the gate. We can see that Low risk is very capable of giving a positive because of the high ammount of data points that we have. High_risk on the other hand doesnt have alot of data so its harder to predict. asy Ensemble AdaBoost Classifier shows the best having .92 for high risk and .94 for low risk. this mean that it wont miss the spot. its also perfect because recall also looks at false negatives meaning the bank wont lose as much money to people that cant pay it back. 

