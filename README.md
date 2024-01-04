# Logistic-Regression
# About LoanTap
LoanTap is an online platform committed to delivering customized loan products to millennials. They innovate in an otherwise dull loan segment, to deliver instant, flexible loans on consumer friendly terms to salaried professionals and businessmen.

The data science team at LoanTap is building an underwriting layer to determine the creditworthiness of MSMEs as well as individuals.

LoanTap deploys formal credit to salaried individuals and businesses 4 main financial instruments:

  1. Personal Loan<br>
  2. EMI Free Loan<br>
  3. Personal Overdraft<br>
  4. Advance Salary Loan<br>
This case study will focus on the underwriting process behind Personal Loan only
# Recommendations
* The optimal strategy to achieve the objective of balancing the risk of increasing NPAs by disbursing loans to defaulters with the opportunity to earn interest by disbursing loans to as many worthy customers as possible: maximise the F1 score along with the area under Precision Recall Curve (precision-recall trade-off).
* More complex classifiers like random forest would give better results compared to logistic regression because they are not restricted by the linearity of decision boundary.
* ROC AUC curve area of 0.79, the model is correctly classifying about 79% of the instances. This is a good performance, but there is still room for improvement.
* By collecting more data, using a more complex model, or tuning the hyperparameters, it is possible to improve the model's performance.
