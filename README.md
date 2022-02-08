# Credit Risk Analysis

## Overview of the analysis
The purpose of this analysis is to analyze the credit card credit databsent from LendingClub wherein the data will undergo machine learning techniques to train and evaluate models using imbalanced-learn and sckikit-learn libraries.  Different methods will be used to evaluate performance of the methods and determine if any of the methods can be used to predict credit risk.  
## Results 
<b>Resampling Methods</b><br>
•	RandomOverSampler
<br>Based on this method, there’s a 65% balanced accuracy score with High Risk getting 1% precision with 61% sensitivity and 2% F1 score.  While the Low Risk has 100% precision with 68% sensitivity and 81% F1 score.  The difference in the scores between High and Low is due to the high number of low risk population compared to the high risk population.
![ROS](https://github.com/karissapadilla/Credit_Risk_Analysis/blob/main/Resources/ROS.png)
Image 1. ROS Screenshot

•	SMOTE
<br>Based on this method, there’s a 62% balanced accuracy score with High Risk getting 1% preceision with 61% sensitivity and 2% F1 score.  While the Low Risk has 100% precision with 64% sensitivity and 78% F1 score.  The difference in the scores between High and Low is due to the high number of low risk population compared to the high risk population.
![SMOTE](https://github.com/karissapadilla/Credit_Risk_Analysis/blob/main/Resources/SMOTE.png)
Image 2. SMOTE Screenshot

•	ClusterCentroids
<br>Based on this method, there’s a 52% balanced accuracy score with High Risk getting 1% precision with 61% sensitivity and 1% F1 score.  While the Low Risk has 100% precision with 43% and 60% F1 score.
![ClusterCentroids](https://github.com/karissapadilla/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroids.png)
Image 3. ClusterCentroids Screenshot

•	SMOTEENN
<br>Based on this method, there’s a 62% balanced accuracy score with High Risk getting 1% precision with 69% sensitivity and 2% F1 score.  While the Low Risk has 100% precision with 54% sensitivity and 70% F1 score.
![SMOTEENN](https://github.com/karissapadilla/Credit_Risk_Analysis/blob/main/Resources/SMOTEENN.png)
Image 4. SMOTEENN Screenshot

<b>Ensemble Methods</b><br>
•	Balanced Random Forest Classifier
<br>Based on this method, there’s a 79% balanced accuracy score with high risk getting 4% precision with 67% sensitivity and 7% F1 score. While low risk has 100% precision with 91% sensitivity and 95% F1 score. 
![Balanced Random Forest Classifier](https://github.com/karissapadilla/Credit_Risk_Analysis/blob/main/Resources/Balanced%20Random%20Forest%20Classifier.png)
Image 5. Balanced Random Forest Classifier Screenshot

•	Easy Ensemble AdaBoost Classifier
<br>Based on this method, there’s a 93% balanced accuracy score with high risk getting 7% precision with 91% sensitivity and 14% F1 score.  While low risk has 100% precision with 94% sensitivity and 97% F1 score. 
![Easy Ensemble AdaBoost Classifier](https://github.com/karissapadilla/Credit_Risk_Analysis/blob/main/Resources/Easy%20Ensemble%20AdaBoost%20Classifier.png)
Image 6. Easy Ensemble AdaBoost Classifier Screenshot

## Summary
Based on the scores from the different methods above, there is really not one method that I would recommend due to the imbalanced scores with precision, sensitivity, and accuracy.  Out of the six methods, the Easy Ensemble AdaBoost Classifier had the best accuracy score of 93%; however, the precision and sensitivity is not balanced.  
