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

## Notebook and Working
The notebook for predicting the success of bank telemarketing follows a series of steps and methodologies to achieve the final prediction. Below are the details:

### Data Preprocessing
- **Loading Data**: The dataset is loaded into a pandas DataFrame.
- **Handling Missing Values**: Missing values are handled by either filling them with appropriate values or dropping the rows/columns.
- **Encoding Categorical Variables**: Categorical variables are encoded using techniques such as one-hot encoding or label encoding.
- **Feature Scaling**: Numerical features are scaled using techniques like StandardScaler or MinMaxScaler.

### Feature Engineering
- **Creating New Features**: New features are created based on existing features to provide more information to the model.
- **Feature Selection**: Important features are selected based on their correlation with the target variable or using feature importance from models.

### Model Training
- **Splitting Data**: The data is split into training and validation sets.
- **Choosing Model**: Machine learning models such as Logistic Regression, Decision Trees, Random Forest, or Gradient Boosting are chosen.
- **Training Model**: The chosen model is trained on the training data.
- **Hyperparameter Tuning**: Hyperparameters of the model are tuned using techniques like GridSearchCV or RandomizedSearchCV.

### Evaluation Metrics
- **Accuracy**: The accuracy of the model is calculated on the validation set.
- **F1 Score**: The F1 score (macro) is calculated to evaluate the model's performance.
- **Confusion Matrix**: A confusion matrix is plotted to visualize the performance of the model.

### Libraries and Tools
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Scikit-learn**: For machine learning algorithms and evaluation metrics.
- **Matplotlib/Seaborn**: For data visualization.

## Links
[kaggle competitions link](https://www.kaggle.com/competitions/predict-the-success-of-bank-telemarketing/overview).\
[kaggle notebook link](https://www.kaggle.com/code/shreeharianbazhagan/23ds3000002-notebook-t32024).

