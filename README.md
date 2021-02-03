# Predicting-Loan-Repayment--Ensemble-Learning
---

> Author: Richard Taracha

> Date: 03/02/2021

![cutomer churn header](https://user-images.githubusercontent.com/67068918/100549903-0de4bc00-3287-11eb-855c-d88a391b50f0.png)

---

### Table of Contents
- [Understanding The Context](#understanding-the-context)
- [Project Deliverable](#project-deliverable)
- [Recording the Experimental Design](#recording-the-experimental-design)
- [Summary Of Findings](#summary-of-findings)
- [Recommendations](#summary-of-findings)
- [Challenging your Solution](#challenging-your-solution)
- [Author Information](#author-information)

---

## Understanding The Context

Working as a Data Scientist for MTN Africa, a leading Telecommunications Company in Africa, there is an effort to understand the behaviour of the company's customers, you are tasked to analyze relevant customer data and develop a solution that will help determine whether a customer will churn. Use the provided dataset to implement your solution. In addition, you will be expected to help relevant stakeholders understand the potential of your developed solution.

#### Technologies and Tools

- Python
- Pandas
- Numpy
- Matplotlib
- Scikit-Learn

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Project Deliverable
Deliverable is a Python notebook with the Classification Analysis.

* Notebook name: Customer churn prediction.ipynb

Dataset name: call-center-data-QueryResult 
</br>
Dataset URL = https://bit.ly/MTNTelcoDataset

Dataset Glossary Name: classification_analysis_glossary
</br>
Dataset Glossary Download Link: https://bit.ly/3gTideq


NB: Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Recording the Experimental Design
1. Load libraries and dataset.
2. Deal with duplicates and missing data.
3. Find and deal with other anomalies.
4. Drop unnecessary columns.
5. Perform univariate and bivariate analysis.
6. Test formulticollinearity.
7. Data modelling.
8. Summarize findings.
9. Make recommendations.
10. Challenge solution.

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Summary Of Findings
* This dataset is very biased: it has disproportionate numbers of those with international plans vs those without international plans, and of those who churned vs those who didn't. Also, this dataset had more records of customers from Area Code 415. Hence, the results cannot really be trusted.

* However, from our analysis, we see that customers who made at least 2 calls to customer service are likely to churn.

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Recommendations
The company should come up with a solution that caters to customers that make two or more calls to customer service. They should also collect more data, preferably those that will make the current dataset more balanced, e.g., more customers from Area Codes 408 and 510, more customers who churned, and more customers subscribed to the international plan.

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Challenging your Solution
* Firstly, a balanced dataset needs to be obtained, where the differences between the distinct values in the 'international_plan' and 'churn' variables are not so great.

* Secondly, all other assumptions need to be met, such as no influential values (outliers)in predictor variables before applying logistic regression.

* Finally, hyperparameter tuning should be carried out on the current models to improve them.

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)

---

## Author Information

- Twitter - https://twitter.com/Vycellous_Drum
- Website - https://richardtaracha.glitch.me/

[Back To The Top](#Customer-Churn-Predicition--Classification-Analysis)
