# Analysis 

The purpose of this activity was to try two different logistic regression models in order to predict safe vs high-risk loans, based on credit data. First, a normal logistic regression model was fit on training data and tested. Then, a new logistic regression model was fit on oversampled data and tested. 

## Regular Logistic Regression Results 

This model had an overall accuracy of 99%, with a balanced accuracy score of 95.3%. 

For safe loans ('0'):
- 1.00 precision: out of all the predicited safe loans, 100% of them were *actually* safe 
- .99 recall: out of *all* real safe loans, 99% of them were predicted to be safe 

For risky loans ('1'):
- .85 precision: out of all the predicted risky loans, 85% of them were *actually* risky
- .91 recall: out of *all* real risky loans, 91% of them were prediced to be risky

## Oversampled Logistic Regression Results 

This model had an overall accuracy of 99%, with a balanced accuracy score of 99.3%. 

For safe loans ('0'):
- 1.00 precision: out of all the predicited safe loans, 100% of them were *actually* safe 
- .99 recall: out of *all* real safe loans, 99% of them were predicted to be safe 

For risky loans ('1'):
- .84 precision: out of all the predicted risky loans, 84% of them were *actually* risky
- .99 recall: out of *all* real risky loans, 99% of them were prediced to be risky

# Overall Model Choice
For this company, I would reccomend the model that was trained on the oversampled data because it showed a higher overall balanced accuracy, and better recall when predicting risky loans. However, using oversampled data to train your model does have a possibility of overfitting your model. I would make this fact known to the company while I am presenting my findings
