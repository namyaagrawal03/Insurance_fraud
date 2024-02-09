**INSURANCE FRAUD DETECTION SYSTEM:**
    Detection of “Auto Insurance Fraud” by analyzing past claims data.
  
  **DATA PREPROCESSING**
  
        REMOVING IRRELEVANT DATA:
          Conducted an analysis to determine the number of unique values for each feature within the dataset.
          Utilized heatmaps to visualize and calculate correlations between features. Dropped data columns with high correlation between them.
          Also removed features that were irrelevant.
          
      ADDRESSING IMBALANCED DATA:
          Incorporated 'Random Oversampling' to address class imbalance in the dataset. 
          On the class with fewer instances (FraudFound_P == 1) to match the number of instances in the majority class (FraudFound_P == 0).

      FEATURE TRANSFORMATION:
          Categorical variables were transformed into binary vectors to represent various categories within each feature.

      SCALING OF FEATURES:
          Applied data scaling techniques (Standard scaling) to normalize feature values.
                                       z = (x - u) / s
           where u is the mean of data and s is the standard deviation

  **MACHINE LEARNING MODEL**
      RANDOM FOREST CLASSIFIER
          The classifier used is random forest classifier.
          It gave the best accuracy among other classifiers.
          Also used Grid Search to find the best value for the estimators in Random Forest.**

   **DATASET OVERVIEW**
    Dataset used was downloaded from kaggle named “fraud_oracle.csv”.
    It has 33 columns including one column for label “FraudFound_P”.
    FraudFound_P have two values 0 and 1.







            




        


