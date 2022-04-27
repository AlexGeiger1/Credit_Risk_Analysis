# Credit_Risk_Analysis

## Purpose 

The  purpose of this analysis was to use different computer learning techniques using credit card data from LendingClub to train and evaluate the models to predict credit risk.  The performance of the models was evaluated by comparing balanced accuracy scores, confusion matrices, recall (sensitivity) and precision scores. 

### Data Sample  models 

The models/algorithms included RandomOverSampler, SMOTE, SMOTEENN,  ClusterCentroids, BalancedRandomForestClassifier, and Easy EnsembleClassifier.  

## Results of Each Machine Learning Model 

 

### Balanced Accuracy  Score 
|Method| Score|
|:----------------|:----------------------|
|RandomOverSampler|			0.6484905987244723 |
|SMOTE| 					0.623523937295285| 
|ClusterCentroids| 			0.623523937295285| 
|SMOTEENN| 					0.5186041311625995| 
|BalancedRandomForestClassifier|	0.7885466545953005| 
|EasyEnsembleClassifier| 		0.9316600714093861 |

 

### Precision Score 

|Method|high_risk  	|low_risk	 |avg	| 
|:----------------|:--------:|:-----:|:-----:|
|RandomOverSampler| 			0.01|		1.00|		.99	| 
|SMOTE					|0.01		|1.00		|.99 |
|ClusterCentroids| 			0.01|		1.00|		.99| 
|SMOTEENN| 					0.01|		1.00|		.99| 
|BalancedRandomForestClassifier| 	0.03|		1.00|		.99| 
|EasyEnsembleClassifier| 		0.09|		1.00|		.99|		 

 

### Recall Score  

|Method|high_risk  	|low_risk	 |avg	| 
|:----------------|:--------:|:-----:|:-----:|
|RandomOverSampler| 			0.63|		0.66|		.66| 
|SMOTE| 					0.62|		0.63|		.63| 
|ClusterCentroids| 			0.57|		0.46|		.46| 
|SMOTEENN| 					0.70|		0.58|		.58| 
|BalancedRandomForestClassifier| 	0.70|		0.87|		.87| 
|EasyEnsembleClassifier| 		0.92|		0.94|		.94|						 

## Summary 

###  

### Recommendation 
