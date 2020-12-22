# Insurance-Churn-Analysis
## Project Overview

Insurance companies around the world operate in a very competitive environment. With various aspects of data collected from millions of customers, it is painstakingly hard to analyze and understand the reason for a customer’s decision to switch to a different insurance provider.

For an industry where customer acquisition and retention are equally important, and the former being a more expensive process, insurance companies rely on data to understand customer behavior to prevent retention. Thus knowing whether a customer is possibly going to switch beforehand gives insurance companies an opportunity to come up with strategies to prevent it from actually happening.

## Methods

- Statistic data description using Pandas,Numpy librarys in Python.
- Data was slpit in 30% test and 70% train subsets.
- Logistic Regression, Random Forest, Support Vector Machine and Neural Netowrk were used.
- Grid Search for parameter tuning.
- SMOTE and ADASYN were used for oversampling.

## Result
### Customer Distribution
![捕获](https://user-images.githubusercontent.com/72762392/102912991-1d9d8d80-444c-11eb-8a9a-b94377e127ca.JPG)

### Classification Report
Because this is an imbalanced dataset, only accruacy couldn't be used as model evaulation. We are more interested in F1 score.
Before applying any resampling methods, our F1 score is around 0.4 - 0.48.
Using SMOTE, we improved F1 score to 0.51.
![image](https://user-images.githubusercontent.com/72762392/102917190-bd5e1a00-4452-11eb-9b20-dcaece4d67df.png)
