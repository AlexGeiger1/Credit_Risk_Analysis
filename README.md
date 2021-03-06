# Credit_Risk_Analysis

# Purpose 

The  purpose of this analysis was to use different computer learning techniques using credit card data from LendingClub to train and evaluate the models to predict credit risk.  The performance of the models was evaluated by comparing balanced accuracy scores, confusion matrices, recall (sensitivity) and precision scores. 

## Data Sample  models 

The models/algorithms included RandomOverSampler, SMOTE, SMOTEENN,  ClusterCentroids, BalancedRandomForestClassifier, and Easy EnsembleClassifier.  

# Results of Each Machine Learning Model 
 

## Balanced Accuracy  Score

- The following is a screenshot of the code used to obtain a balanced accuracy score, and underneath is a table of the all the seperate methods' score from the code.

![Balanced Accuracy Score](https://github.com/AlexGeiger1/Credit_Risk_Analysis/blob/main/Resources/balanced%20accuracy%20score.png)

|Method| Score|
|:----------------|:----------------------|
|RandomOverSampler|			0.6484905987244723 |
|SMOTE| 					0.623523937295285| 
|ClusterCentroids| 			0.623523937295285| 
|SMOTEENN| 					0.5186041311625995| 
|BalancedRandomForestClassifier|	0.7885466545953005| 
|EasyEnsembleClassifier| 		0.9316600714093861 |

 

## Confusion Matrix 

- The following is a screenshot of the code for the algorithm called a Confusion Matrix, which provides the recall and precision scores.
- Underneath are tables of the results for high-risk and low-risk for each technique.

![Precision Score](https://github.com/AlexGeiger1/Credit_Risk_Analysis/blob/main/Resources/Confusion%20Matrix.png)

### Precision Score

|Method|high_risk  	|low_risk	 |avg	| 
|:----------------|:--------:|:-----:|:-----:|
|RandomOverSampler| 			0.01|		1.00|		.99	| 
|SMOTE					|0.01		|1.00		|.99 |
|ClusterCentroids| 			0.01|		1.00|		.99| 
|SMOTEENN| 					0.01|		1.00|		.99| 
|BalancedRandomForestClassifier| 	0.03|		1.00|		.99| 
|EasyEnsembleClassifier| 		0.09|		1.00|		.99|		 

 

### Recall Score (Sensitivity Score)  

|Method|high_risk  	|low_risk	 |avg	| 
|:----------------|:--------:|:-----:|:-----:|
|RandomOverSampler| 			0.63|		0.66|		.66| 
|SMOTE| 					0.62|		0.63|		.63| 
|ClusterCentroids| 			0.57|		0.46|		.46| 
|SMOTEENN| 					0.70|		0.58|		.58| 
|BalancedRandomForestClassifier| 	0.70|		0.87|		.87| 
|EasyEnsembleClassifier| 		0.92|		0.94|		.94|						 

# Summary 
## Conclusion
The balanced accuracy score had some variation between the different techniques of Machine learning with the two ensemble classifiers scoring the better in comparison to the other methods. The precision score was extremely low for all 6 different models on the high-risk section, however all the methods performed very well on the low-risk test. Finally, when reviewing the Recall Scores, it is apparent that the ensemble classifiers scored higher on average than the other forms of machine learning.  

## Recommendation 
With the EasyEnsembleClassifier scoring the highest on almost every test, this form of machine learning is my recommendation. However, it is extremely likely that this method will return false positives. 
