![credit card fraud](https://user-images.githubusercontent.com/88999980/161479534-32cdd092-8e3c-4ed7-af30-4b3ed611215a.jpeg)
#  Predicting whether a customer will default on his/her credit card Capstone Project
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments
## Data Description
* Attribute Information:
* This research employed a binary variable, default payment (Yes = 1, No = 0), as the response variable. This study reviewed the literature and used the following 23 variables as explanatory variables:
* X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
* X2: Gender (1 = male; 2 = female).
* X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
* X4: Marital status (1 = married; 2 = single; 3 = others).
* X5: Age (year).
* X6 - X11: History of past payment. We tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; 
* X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
* X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
* X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.

## CONTENTS
* Introduction
* Problem Statement
* Methodology
* Loading the data
* Exploratory Data Analysis
* Treating missing values and outliers
* Feature engineering
* Train test split
* Data Modeling
* Model interpretation
* Train and test interpretation
* Conclusion
## METHODOLOGY
![image](https://user-images.githubusercontent.com/88999980/174426294-7d068558-83e0-4f38-8e6f-3e1a3accafab.png)
## BALANCING THE UNBALANCE DATASET
![image](https://user-images.githubusercontent.com/88999980/174426378-5d5c800b-d0d4-431b-b175-e5a426e92fc1.png)
## SMOTE (OVERSAMPLING METHOD)
Synthetic Minority Oversampling Technique (SMOTE)
This technique generates synthetic data for the minority class.
SMOTE (Synthetic Minority Oversampling Technique) works by randomly picking a point from the minority class and computing the k-nearest neighbors for this point. The synthetic points are added between the chosen point and its neighbors.
![image](https://user-images.githubusercontent.com/88999980/174426425-41015750-2fe9-41e8-b3fd-69e5361622d7.png)
![image](https://user-images.githubusercontent.com/88999980/174426430-f717ddae-7314-43bb-8df0-9da5804f49e8.png)
## CONCLUSION

![image](https://user-images.githubusercontent.com/88999980/174426461-dedfc5b9-e0a7-48b0-8688-8e14293d1b37.png)






