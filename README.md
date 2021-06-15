
## Abstract 

The task is to analyse data and create a model which would predict if item will be sold in 24 hours. Dataset contains 76 features from which 27 are categorical and 36 continuous. Target proportions are not equal. For feature evaluation chi2 and anova tests were conducted. Data analysis shown that most important features are cities, brands, catalog_codes, window_item_sold, total_negative_feadback_count, birthday and phone_verification_local_time. However, on PCA projections no visible decision boundary is visible, making classification task hard.

Few machine learning models were trained: logistic regression, SVM, gradient boosting classifier and KNN. Gradient boosting classifier yielded best score = ~70%. 


## Instructions: 

Everything should be straightforward, just go over the steps of the notebook:

To load models: 

1. generate targets in "generate target" section
2. in Model section there is a cell which does that. However these models are trained on preprocessed data, so in case of testing execution of cells in section "Pipeline" and cells from ""Model" to "Data on first 3 principal components" are needed.
3. Final classifier is loaded in section "Final Classifier"


Other notes: 
1. In case plots of Pricipal components not shown, execution of all main sections are required.  
