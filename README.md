# Ensemble-Learning--Kopo-Kopo-Loan-Repayment-Prediction
---

> Author: Richard Taracha

> Date: 03/02/2021

![kopo-kopo](https://user-images.githubusercontent.com/67068918/106791402-ebe02f00-6665-11eb-9892-c74f7ba5b9cc.png)

---

### Table of Contents
- [Background Information](#backgroung-information)
- [Understanding The Context](#understanding-the-context)
- [Project Deliverable](#project-deliverable)
- [Recording the Experimental Design](#recording-the-experimental-design)
- [Summary Of Findings](#summary-of-findings)
- [Recommendations](#summary-of-findings)
- [Challenging your Solution](#challenging-your-solution)
- [Author Information](#author-information)

---

## Background Information
Koppokoppo, is a company that offers market-appropriate solutions to enable and incentivize businesses to go digital. The company partners with financial institutions, mobile operators and major retailers who are interested in marketing new payment services to small and medium enterprises. In turn, the company offers small and medium enterprises loans.
</br>
Website: https://kopokopo.co.ke/

## Understanding The Context

As a Data Scientist, you are required to create a model that will allow Koppokoppo to provide a solution is able to predict whether a loan offered to the certain small and medium enterprise will be paid off.

#### Technologies and Tools

- Python
- Pandas
- Numpy
- Matplotlib
- Scikit-Learn

[Back To The Top](#Ensemble-Learning--Kopo-Kopo-Loan-Repayment-Prediction)

---

## Project Deliverable
Deliverable is a Python notebook with the Ensembel Learning Techniques (Bagging and Boosting).

* Notebook name: Ensemble Learning with Scikit-Learn.ipynb

Dataset 1 name: kopokopo_dataset - datasets_602860_1082167_SBAcase.11.13.17 
</br>
Dataset 2 name: kopokopo_clean.csv
</br>
Dataset URL = https://bit.ly/KoppoKoppoDS

Dataset Glossary Name: Koppokoppo - Glossary - t0001-10.1080_10691898.2018.1434342 (1).csv
</br>
Dataset Glossary Download Link: https://bit.ly/KoppokoppoGlossary


NB: Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

[Back To The Top](#Ensemble-Learning--Kopo-Kopo-Loan-Repayment-Prediction)

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