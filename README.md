# Predict the Success of Bank telemarketing
MLP Project T32024

## Overview
- MLP Project T32024
- After joining the competition go to the code tab and create a New Notebook.
- Keep notebook name as YourRollNo-notebook- t32024 . (i.e 21f1001234-notebook-t32024)
- Share the notebook with iitmbscs2008p collaborator. View access is sufficient and make/keep it private.
- Build your first ML model (dummy or any other)
- predict target of the test data as store as given in sample_submission.csv
- store predictions in a DataFrame with "id" and "target columns.
- save the DataFrame in a csv and make a submission using that csv
- Change your team name to Your Roll No (i.e 21f1001234)

## Description
The data is related with direct marketing campaigns of a banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

## Evaluation
The evaluation section describes how submissions will be scored and how participants should format their submissions.

Submissions are evaluated on f1_score(average='macro') between the predicted classes and the True target.

## Submission File
For each id in the test set, you must predict a class for the target variable. The file should contain a header and have the following format:
| id   | target   |
| ---- | -------- |
| 0    | "yes"    |
| 1    | "no"     |
| etc. | "yes/no" |

## Dataset Description
The data is related with direct marketing campaigns of a banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

## Files
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format

## Input variables:
1. last contact date: last contact date
2. age (numeric)
3. job : type of job
4. marital : marital status (categorical: "married","divorced","single"; note: "divorced" means divorced or widowed)
5. education (categorical: "unknown","secondary","primary","tertiary")
6. default: has credit in default? (binary: "yes","no")
7. balance: average yearly balance, in euros (numeric)
8. housing: has housing loan? (binary: "yes","no")
9. loan: has personal loan? (binary: "yes","no")
10. contact: contact communication type (categorical: "unknown","telephone","cellular")
11. duration: last contact duration, in seconds (numeric)
12. campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)
13. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric, -1 means client was not previously contacted)
14. previous: number of contacts performed before this campaign and for this client (numeric)
15. poutcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

## Output variable (desired target):
16 target: has the client subscribed a term deposit? (binary: "yes","no")

## Links
[kaggle competitions link](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing/overview).\
[kaggle notebook link](https://www.kaggle.com/code/shreeharianbazhagan/23ds3000002-notebook-t32024).

