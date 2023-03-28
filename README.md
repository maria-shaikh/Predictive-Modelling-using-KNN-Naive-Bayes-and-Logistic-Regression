# Predictive-Modelling-using-KNN-Naive-Bayes-and-Logistic-Regression
The goal of this project is to develop classification regression models to classify personal loan accounts as “profitable” or “not profitable”. 

![image](https://user-images.githubusercontent.com/102799924/228106110-c390964f-0e16-4a0e-84c0-f453675799fe.png)

The data in the spreadsheet creditv2.csv contains data pertaining to 800 personal loan accounts at a bank. 

When a new applicant applies for credit, as a part of the application, the company collects information which is available in the form of Variables 2 to 21. The company then decides an amount to be credited (the variable CREDIT_EXTENDED). For these 800 accounts, we also have information on how profitable each account turned out to be (variable NPV). A negative value indicates a net loss, and this typically happens when the debtor defaults on his/her payments or if the loan is renegotiated.

The goal in this case is to investigate how one can use this data to better manage the bank's credit extension program. Specifically, our goal is to develop a classification regression model to classify a new account as “profitable” or “not profitable”. 

For the purpose of this project, we have developed 3 classification regression models:
1. K-nearest neighbors
2. Naïve Bayes
3. Logistic regression

Finally, we discuss which model has the best prediction performance using ROC curves for the three models. 


