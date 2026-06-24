GitHub Link : https://github.com/kimkok-UCBerkeleyHaas/Module-17_Assignment-17-1/

# Module-17_Assignment-17-1
Learning Outcome Addressed 
  - Apply various classification methods to a business problem. 
  - Compare the results of k-nearest neighbors, logistic regression, decision trees, and support vector machines.

Overview - 
In this third practical application assignment, your goal is to compare the performance of the classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines) you encountered in this section of the program. You will use a dataset related to the marketing of bank products over the telephone.

Data - 
The dataset you will use comes from the [UC Irvine Machine Learning Repository Links ](https://archive.ics.uci.edu/ml/datasets/bank+marketing) The data is from a Portuguese banking institution and is a collection of the results of multiple marketing campaigns. Please see the following link to access the assignment:

[Required Assignment 17.1](https://mo-pcco.s3.us-east-1.amazonaws.com/BH-PCMLAI-R2-Master-EMCODE/module17/module17_starter.zip)

Deliverables - 
After understanding, preparing, and modeling your data, build a Jupyter Notebook that includes a clear statement demonstrating your understanding of the business problem, a correct and concise interpretation of descriptive and inferential statistics, your findings (including actionable insights), and next steps and recommendations.

**Goal:** Compare the performance of K-Nearest Neighbors, Logistic Regression, Decision Trees, and Support Vector Machines using the Portuguese Bank Marketing dataset to predict whether a customer will subscribe to a term deposit (`y`). 
1. Business Understanding 
- The objective of this project is to analyze a dataset from a Portuguese banking institution's telemarketing campaigns to optimize their marketing efficiency.  
- Direct marketing campaigns over the phone represent a significant resource investment. By leveraging historical campaign data, we aim to build a predictive classification model that identifies which customers are most likely to subscribe to a long-term deposit (target variable `y`).  
 
**Business Success Metric:** Maximize the efficiency of telemarketing calls by minimizing false positives (calling individuals who won't subscribe) and maximizing true positives (successfully identifying subscribers), thereby boosting conversion rates and reducing operational costs. We will use **ROC-AUC** and **F1-Score** as our primary evaluation metrics to handle class imbalance while optimizing predictive power.


