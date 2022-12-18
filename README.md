# VoltaML_Assignment
# Automatic Ticket classification for complaints
### This model can automatically classify customer complaints based on the products and services that the ticket mentions.

## Problem Statement
We need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

You will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, you need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:
  - Credit card / Prepaid card
  - Bank account services
  - Theft/Dispute reporting
  - Mortgages/loans
  - Others

With the help of topic modelling, you will be able to map each ticket onto its respective department/category. You can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.

### **Dataset**
- NOTE :- The required dataset is present in "Complaints.zip" file. Kindly unzip it to get the required dataset in JSON format.
- NOTE :- We also need to change the filename for the JSON format dataset from "complaints-2021-05-14_08_16.json" to "complaints.json".


### **Pipelines that has been used are:**

I have performed the following eight major tasks to complete this assignment:

1.  Data loading
2. Text preprocessing
3. Exploratory data analysis (EDA)
4. Feature extraction
5. Topic modelling 
6. Model building using supervised learning
7. Model training and evaluation
8. Model inference


## Summary
The best model for Prediction of ticket classification was found to be LogisticRegression with GridSearchCV with ROC_AUC score of 0.95 and 0.93 for train and test cases respectively.




