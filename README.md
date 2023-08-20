# TREUE-TECHNOLOGIES-BANK-CUSTOMER-CHURN-PREDICTION-

IMPORTING LIBRARIES:

     Importing All the libraries numpy, pandas , matplotlib, seaborn, Logistic Regression , Random Forest, XGBClassifier, SVC, and accuracy models.
     UPLOADING THE CSV FILE:

     Uploading the customer churn csv file using pandas library .

PERFORMING EXPLORATORY DATA ANALYSIS:

     To check the null values present in the given data using the isnull() .sum()
     
     To check the unique values present the given data using unique()
     
     drop the unwanted columns
     
     Plot the properties customer churn and retained subplots

FEATURE ENGINEERING:

    seek to add features that are likely to have an impact on the probability of churning

MODEL FITTING:

    Fit the models are Logistic regression , XGBClassifier, Random Forest Method , SVC
    
    Plot the ROC curve for all the models

CHOOSE THE BEST MODEL:

    By comparing different machine learning models based on r2 score it is found that Random Forest Model works best for this dataset.
    
    Plot the ROC Curve for random Forest model

CONCLUSION:

    The precision of the model on previousy unseen test data is slightly higher with regard to predicting 1's i.e. those customers that churn. However, in as much 
    as the model has a high accuracy, it still misses about half of those who end up churning. This could be imprved by providing retraining the model with more 
    data over time while in the meantime working with the model to save the 41% that would have churned
