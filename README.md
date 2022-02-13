# Credit_Risk_Analysis
Overview of the analysis:
This Challenge was to employ different techniques in order to train and evaluate various machine learning models to predict credit risk. The Algorithms we used to conduct the analysis were:

Oversample - RandomOverSampler and SMOTE algorithms.
Undersample - ClusterCentroids to resample the data.
Combinatorial approach of over- and undersampling using the SMOTEENN algorithm.
BalancedRandomForestClassifier and EasyEnsembleClassifier that reduce bias and predict credit risk.

1. In the Naive Random Oversampling results the Balanced_accuracy_score was 63.7%.
2. The high_risk precision is about 1% only with 61% sensitivity, which shows an F1 value of 2%.
3. Due to a higher/ imbalanced number seen in the low_risk population, the precision is 100% with a sensitivity of 66%.


##UnderSample Results

1. The Balanced_accuracy_score was 53%.
2. The high_risk precision is about 1% only with 61% sensitivity, which shows an F1 value of 1%.
3. Due to a higher/ imbalanced number seen in the low_risk population, the precision is 99% with a sensitivity of 45%.
 

##Smote Results

1. The Balanced_accuracy_score was 65.5%.
2. The high_risk precision is about 1% only with 64% sensitivity, which shows an F1 value of 2%.
3. Due to a higher/ imbalanced number seen in the low_risk population, the precision is 99% with a sensitivity of 67%.

##Combinatorial approach Results

1. The Balanced_accuracy_score was 62.4%.
2. The high_risk precision is about 1% only with 70% sensitivity, which shows an F1 value of 2%.
3. Due to a higher/ imbalanced number seen in the low_risk population, the precision is 100% with a sensitivity of 55%.

##BalancedRandomForestClassifier Results

1. The Balanced_accuracy_score improved to 78.7%.
2. The high_risk precision is about 4% only with 67% sensitivity, which shows an F1 value of 7%.
3. Due to a higher/ imbalanced number seen in the low_risk population, the precision is 100% with a sensitivity of 91%.

##EasyEnsembleClassifier Results

1. The Balanced_accuracy_score was the highest at 92.5%.
2. The high_risk precision is about 7% only with 91% sensitivity, which shows an F1 value of 14%.
3. Due to a higher/ imbalanced number seen in the low_risk population, the precision is 100% with a sensitivity of 94%.


#Summary

It is evident that precision analysis in the various models was not a sufficient way to predict a high credit risk. 
The EasyEnsembleClassifer model predicted the best results primarily on the sensitivity which was the best way to predict high credit risk.
There was a high number of imbalance noted in the low_risk populations for each model that flagged as false-positives in the high risk category which could negatively affect the lender in declining loans to customers that would be repaid.  
Additional analysis should be conducted to refine their criteria that would better predict high credit risk within the low_risk populations, so that the imbalance is not as big. 

