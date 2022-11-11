# Problem Statement
we are going to work on binary classification problem, where we got some information about sample of peoples , and we need to predict whether we should give some one a loan or not depending on his information .

# Content
we actually have a few sample size (614 rows), so we will go with machine learning techniques to solve our problem.

This Dataset contains total 12 features
1-Loan_ID

2-Gender

3-Married

4-Education

5-Self_Employed

6-ApplicantIncome

7-CoapplicantIncome

8-LoanAmount

9-Loan_Amount_Term

10-Credit_History

11-Property_Area

and the predicate column (Loan_Status)

# Note
After making processing on the data I got some outliers so before disposal it I calculate it.
And at the end I can't remove the outliers as it represent 6.35 % of the column.

# conclusion
Due to high number of features I use PCA in our situation 

Model I used is (support Vector machine Classification algorithm).

and I got:

Accuracy is 83.77 %

precision is 82.58 %

recall is 98.20 %
