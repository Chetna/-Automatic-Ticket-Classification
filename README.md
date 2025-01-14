# Automatic-Ticket-Classification

# Case Study: Automatic Ticket Classification
Welcome to this case study on 'Automatic Ticket Classification'. Let's start the segment by understanding the problem statement from Alankar and getting an idea of the case study.

In this case study, you will create a model that can automatically classify customer complaints based on the products and services that the ticket mentions.

# Problem statement

For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers.

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

In this case study, you will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans.

3 Business goal
You need to build a model that is able to classify customer complaints based on the products/services. By doing so, you can segregate these tickets into their relevant categories and, therefore, help in the quick resolution of the issue.

With the help of non-negative matrix factorization (NMF), an approach under topic modelling, you will detect patterns and recurring words present in each ticket. This can be then used to understand the important features for each cluster of categories. By segregating the clusters, you will be able to identify the topics of the customer complaints.

You will be doing topic modelling on the .json data provided by the company. Since this data is not labelled, you need to apply NMF to analyse patterns and classify tickets into the following five clusters based on their products/services:

Credit card / Prepaid card
Bank account services
Theft/Dispute reporting
Mortgages/loans
Others
With the help of topic modelling, you will be able to map each ticket onto its respective department/category. You can then use this data to train any supervised model such as logistic regression, decision tree or random forest. Using this trained model, you can classify any new customer complaint support ticket into its relevant department.

# Dataset
Let's first downloadthe data set.

The data set given to you is in the .json format and contains 78,313 customer complaints with 22 features. You need to convert this to a dataframe in order to process the given complaints.

# Expected tasks
You need to perform the following eight major tasks to complete the assignment:

Data loading
Text preprocessing
Exploratory data analysis (EDA)
Feature extraction
Topic modelling
Model building using supervised learning
Model training and evaluation
Model inference
S.no	Model	F1 Score
0	Naive Bayes	0.76
1	Logistic Regression	0.94
2	Decision Tree	0.84
3	Random Forest	0.72
As per the F1 score of all the 4 models, Logistic Regression performs best with F1 score : 0.94
