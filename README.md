# Credit_Risk_Analysis

## Overview of the analysis 
- The purpose of the Credit Risk Analysis is to use skills in data preparartion, statistical reasoning, and machine learning to predict credit risk. SInce credit risk is an inherently unbalanced classification problem. Therefore, I employed different techniquies to train and evaluate models with unbalanced classes. Using Pythons imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. 

## Results
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

- Naive Random Oversampling Model
   ![Naive Random Oversampling](https://user-images.githubusercontent.com/16258584/107434338-4a872c00-6af0-11eb-9a4a-edf01a3614e5.png)
  
  - The Naive Random Oversampling model had an accuracy of 64%. The presision of the classification on the data set was 99% with a recal of 62%.

- SMOTE Oversampling Model
   ![SMOTE Oversampling](https://user-images.githubusercontent.com/16258584/107434342-4ce98600-6af0-11eb-9776-3bd26fcfd2ce.png)
  
  - The Smote Oversampling model had a slightly higher accuracy of 65%. The presision of of the classification on the data set was 99% with a recal at 69%.

- Undersampling Model
   ![Undersampling](https://user-images.githubusercontent.com/16258584/107434344-4e1ab300-6af0-11eb-8b0e-b1b828d88531.png)
  
  - The undersampling model had a accuacy score of 65%. The presision of the classification on the data set was 99% with a recal at 53%.

- Combination Oversampling and Undersampling Model
   ![Combination Over and Under Sampling](https://user-images.githubusercontent.com/16258584/107434347-4f4be000-6af0-11eb-89e2-b26050ae0f7f.png)
  
  - The Combination of Oversampling and Undersampling had an accuracy score of about 57%. The presision of of the classification on the data set was 99% with a recal at 57%.

- Balanced Random Forest Classifier Model
   ![Balanced Random Forest Classifier ](https://user-images.githubusercontent.com/16258584/107434353-5115a380-6af0-11eb-9881-00ca36fadcb1.png)

  - The Balanced Random Forest Classifier had an accuracy score of about 79%. The presision of of the classification on the data set was 99% with a recal at 87%.

- Easy Ensemble AdaBoost Classifier Model
   ![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/16258584/107434365-54a92a80-6af0-11eb-8e92-50ebefc14aaf.png)
  
  - The Easy Ensemble AdaBoost Classifier had an accuracy score of about 93%. The presision of of the classification on the data set was 99% with a recal at 94%.


Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
