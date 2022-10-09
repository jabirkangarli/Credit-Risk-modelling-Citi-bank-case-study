# Credit Risk Modeling City Bank Case Study.

The project was conducted by A. D. Lopez, J. Kangarli and S. Bozheku to determine the probability of default of Apple company given by Citi bank as a case study and increase the accuracy of the final model by 20 percent.


## 1. Business problem

After the 2008 financial crisis, banks began to pay more attention to credit risk, which is considered one of the main causes of the crisis.

Credit risk occurs when a borrower fails to make required payments on a debt. For financial institutions and other lenders, the risk is an inherent part of the lending
Paradigm. It is difficult to determine the amount of risk associated with any loan.
The probability of default, the amount of the receivable at the time of default, the expected value of the loan at the time of default, and the total loss 
in the event of default are all factors that enter into the complex credit risk calculation. Credit institutions today have a plethora of models for estimating credit risk and thus the probability of default. These models look for patterns of behavior from historical data to guess how a consumer will behave in the future.

Models used to predict binary outcomes such as default/non-default include logistic regression, decision trees, neural networks, and Naive Bayes classifiers. However, despite their diversity and their undeniable benefits for banking system stability, these models are not always appropriate for
the complex circumstances that characterize many economies.

CITI, one of the leading commercial banks in the world, makes great efforts and teamwork to develop models and to have solid results from the developed models
that assess the credit risk of its customers.

### The objective 
Our case study objective is to develop a model that can be used to evaluate the one-year probability of default of a company. We worked with two given data sets to develop a model that produces better results than the original model. The original dataset used to develop the original model included debtors from the North America region and their financial variables.

## Conclusion
The main problem with this project was working with an extremely unbalanced data set. The logit regression model implemented by the Citi team was already giving quite good results, so the area of improvement was very narrow. Despite this, and after a fairly sophisticated understanding of their code and model, a theoretical understanding of the variables added new variables to the original model that produced a slight improvement. To achieve an even greater improvement, 3 models were tested and the Random Forest Classifier, which uses the down-sampling technique to cope with the imbalance of the data, was found to be the best. A final Accuracy Ratio (AR) of 89% and an Area Under the ROC Curve (ROC_AUC) of 94% were achieved, which is considered a quite good improvement.
