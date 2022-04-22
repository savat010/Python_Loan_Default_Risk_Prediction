# CSOM_MSBA_6420_Home_Credit
As part of our MSBA 6420 - Predicitive Analytics course for the Spring 2022 Batch, we have created a completed solution of the [Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk) Kaggle Compeititon.

The Repository is divided into 3 parts -  
1.  EDA - The competition involves working with credit repayments and credit lending dataset. We have done an extensive EDA to understand the features.
2.  Data Aggregation - This is the script we used to aggregate multiple datasets onto just one single dataset. For the ease we have uploaded the ADS onto a public kaggle dataset. [Dataset](https://www.kaggle.com/datasets/manishcjain/msba-6420-predictive-analytics-project)
3.  Modeling - We built 3 different models for this challenge. Our final model has a public score of 0.79930 (surpasing the best official score).
  * Logistic Regression - This is our base model. Its simple but did not give us more enhancements with current features.
  * XGBoost - We use Bayesian Optimization to fine tune this model. 
  * LightGBM - Using Bayesian Optimization, we have been able to build a powerful classifier. We also explored OOF predicitions and feature selection in this model.

**Summary of all our models**
|Model | Public Score on Kaggle |
|------|------------------------|
|Logistic Regression with All features | 0.78106 |
|Logistic Regression	Top 90% importance features	|0.77937|
|XGBoost All features	|0.79664|
|XGBoost	Top 400 features	|0.79712|	
|LightGBM All features |	0.79765|
|LightGBM All features (no imbalance HP)	|0.79930|
|LightGBM All features OOF prediction|	0.79777|
|LightGBM Top 400 features|	0.79782|

## Our Best Score on Kaggle

![image](https://media.github.umn.edu/user/22674/files/d00debdc-0467-4895-bdc0-6a923bece72a)




