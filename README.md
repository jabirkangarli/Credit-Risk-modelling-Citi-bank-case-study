# Credit-Risk-Modelling-City-bank-case-study
The project is done by A. D. Lopez, J.Kangarli, and S.Bozheku to find the probability of default of Apple which was a case study given by Citi bank and accuracy of the final model increased by 20 percent.


## 1. Business Problem

Following the financial crisis of 2008, banks began to pay more attention to credit risk, which is believed to be among the root causes of the crisis.

Credit risk occurs when a borrower fails to make required payments on a debt. For financial institutions and other lenders, the risk is an inherent part of the lending
paradigm. It is difficult to determine the level of risk associated with each loan.
The probability of default, the amount of exposure at the time of default, how much the loan is expected to be worth at the time of default, and the overall loss 
if there is a default are all factors that go into the complex credit risk calculation. Credit institutions now have a plethora of models at their disposal for estimating credit risk and, thus, the likelihood of default. 
These models look for behavioral patterns from historical data to guess how a consumer will behave in the future.

Some of the models used for predicting binary outcomes such as default/non-default include logistic regression, decision trees, neural networks, and Naive Bayes classifier. However, despite their diversity and undeniable benefits to banking system stability, these models are not always adequate to deal with
the complex circumstances that characterize many economies.

CITI, as one of the leading corporate banks in the world, puts a huge amount of effort and teamwork to develop models and have solid outputs of the developed models
which assess their clients’ credit risk.

The aim of our case is to build a model which is assessing one-year probability of default of a company. We worked on two given datasets to develop a model 
which would give better results than the original one. The original dataset used for developing the original model contained obligors from North America region 
and their financials variables.


## 2. Models used in the analysis
2.1 Random Forest

2.2 XGBoost

2.3 LightGBM


## Conclusion
The main struggle of this project has been working with an extremely imbalanced dataset. The Logit Regression model implemented by Citi team was also having already quite good results, which made the range of improvement very narrow.
Eventhough and after a quite demanding understanding of their code and model, by a theoretical understanding of the variables, new ones were added to the original model and made a slight improvement on it.
In order to get an even bigger improvement 3 models were tested, with Random Forest Classifier, using Down-Sampling techinique to deal with the imbalance of the data, being the best one. A final Accuracy Ratio (AR) of 89% and an Area Under the ROC Curve (ROC_AUC) of 94% was reached, which is consider a quite good improvement.
