# Capstone Project: Craft Beer Segmentation 

I took data on over 1.5m beer reviews and applied clustering (K-means) to identify beer segments based on review ratings, volume of reviews and recency of review. 

Following this, I applied applied oversampling (using SMOTE) to address imbalanced dataset before running classification models 
(Logistic, RandomForest, Gradient Boosting) with aim of predicting the likelihood of beer being in particular segment of interest to brewery. 
However, decline in Precision scores on test data meant these models would not generalise if applied to new review data.

Final recommendation based on analysis, segmentation and modelling was to develop a Seasonal Wild Ale.