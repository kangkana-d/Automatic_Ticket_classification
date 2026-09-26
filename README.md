# Automatic Ticket Classification using NLP and ML
## Problem Statement
For a financial company, customer complaints carry a lot of importance, as they are often an indicator of the shortcomings in their products and services. If these complaints are resolved efficiently in time, they can bring down customer dissatisfaction to a minimum and retain them with stronger loyalty. This also gives them an idea of how to continuously improve their services to attract more customers. 

These customer complaints are unstructured text data; so, traditionally, companies need to allocate the task of evaluating and assigning each ticket to the relevant department to multiple support employees. This becomes tedious as the company grows and has a large customer base.

 

In this case study, you will be working as an NLP engineer for a financial company that wants to automate its customer support tickets system. As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans. 

## Business goal

The primary objective of this project is to develop an automated complaint classification system that can identify the product or service associated with a customer complaint and route it to the appropriate department for faster resolution.

Since the complaint data provided by the company is unlabelled, we will first use Topic Modelling, specifically Non-Negative Matrix Factorization (NMF), to uncover hidden themes and patterns within the customer complaint tickets. By analyzing frequently occurring words and phrases, NMF will help us identify distinct topics that correspond to different business categories.

##  business categories:
Based on the identified topics, complaints will be mapped to the following

- [Credit Card / Prepaid Card]
- [Bank Account Services]
- [Theft / Dispute Reporting]
- [Mortgages / Loans]
- [Others]

## Solution

To automate the customer support ticket system, we will use NLP techniques to process and analyze the text data. We will apply ML algorithms to classify support tickets based on their content and assign them to the relevant team. The ML component of this project utilizes a powerful algorithm that predicts the ticket's category based on the content of the ticket, achieving high accuracy rates.

## Features

- Automatic ticket classification using NLP and ML algorithms
- Accurate identification and categorization of support tickets
- Efficient assignment of support tickets to the relevant team for swift resolution
- Comprehensive documentation and step-by-step guide for using and integrating the system with existing support workflows
- Open-source codebase for customization and enhancement of the system to fit specific needs.

## Model Evaluation Metrics

The following table summarizes the evaluation metrics for each of the models used in this project:

| Model                   | Accuracy | Precision | Recall | F1 Score | ROC AUC Score |
|-------------------------|---------|-----------|--------|----------|--------------|
| Logistic Regression     | 0.91    | 0.91      | 0.91   | 0.91     | 0.99         |
| DecisionTreeClassifier  | 0.78    | 0.78      | 0.78   | 0.78     | 0.86         |
| RandomForestClassifier  | 0.82    | 0.83      | 0.82   | 0.81     | 0.97         |
| MultinomialNB           | 0.71    | 0.74      | 0.71   | 0.67     | 0.94         |
| XGBClassifier           | 0.91    | 0.91      | 0.91   | 0.91     | 0.99         |

These metrics provide a measure of how well each model performed on the test dataset. The metrics used to evaluate the models are:

- Accuracy: The proportion of true results (both true positives and true negatives) among the total number of cases examined.
- Precision: The proportion of true positives among the total number of cases predicted as positive.
- Recall: The proportion of true positives among the total number of actual positive cases.
- F1 Score: The harmonic mean of precision and recall.
- ROC AUC Score: The area under the Receiver Operating Characteristic (ROC) curve, which measures the performance of the model at different classification thresholds.

Based on these metrics, the Logistic Regression and XGBClassifier models performed the best, with high accuracy, precision, recall, F1 score, and ROC AUC score. The DecisionTreeClassifier and RandomForestClassifier models also performed reasonably well, with an accuracy of 0.78 and 0.82, respectively. The MultinomialNB model had the lowest performance, with an accuracy of 0.71.

## Technologies

- Python
- Natural Language Processing
- Machine Learning
- Data Science

## Conclusion

"Automatic Ticket Classification using NLP and ML" is a valuable resource for any organization seeking to streamline their support ticket classification and resolution process. The automation of the customer support ticket system using NLP and ML techniques allows companies to efficiently identify and categorize support tickets, assign them to the relevant team for swift resolution, and continuously improve their products and services.
