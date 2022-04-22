# CSOM_MSBA_6420_Home_Credit
As part of our MSBA 6420 - Predicitive Analytics course for the Spring 2022 Batch, we have created a completed solution of the [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk) Kaggle Compeititon.

The Repository is divided into 3 parts -  
1.  EDA - The competition involves working with credit repayments and credit lending dataset. We have done an extensive EDA to understand the features.
2.  Data Aggregation - This is the script we used to aggregate multiple datasets onto just one single dataset. For the ease we have uploaded the ADS onto a public kaggle dataset. [Dataset](https://www.kaggle.com/datasets/manishcjain/msba-6420-predictive-analytics-project)
3.  Modeling - We built 3 different models for this challenge. Our final model has a public score of 0.79930 (surpasing the best official score).
  * Logistic Regression - This is our base model. With a extensive feature engineering, even this model has reached 0.78 score
  * XGBoost - We use Bayesian Optimization to fine tune this model. Best score for this model is 
  * LightGBM - Using Bayesian Optimization, we have been able to build a powerful classifier. We also explored OOF predicitions and feature selection in this model. Best Score for this is 0.79930



