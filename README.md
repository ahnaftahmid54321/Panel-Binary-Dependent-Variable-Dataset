# Panel-Binary-Dependent-Variable-Dataset
Analyzing Both Panel dataset and Binary Dependent Variable Dataset


Description of Panel Dataset 

The dataset shows US panel data from 1983-1997. Using USSeatBelts, we are trying to answer how the number of fatalities per million of traffic miles (fatalities) is affected by seatbelt usage rate (seatbelt), whether there is a 65 mile per hour speed limit (speed65), whether there is a maximum of 0.08 blood alcohol content (alcohol), the median per capita income (income), and mean age (age). USSeatBelts can be found in the AER library: https://cran.r-project.org/web/packages/AER/AER.pdf

Description of Binary Dependent Variable Dataset

We are trying to answer whether a person’s credit card application will be accepted or rejected based on these 5 factors and they are: number of major derogatory reports(reports), their age(age), their income(income), whether they own a home or not(owner), and the number of dependents they have(dependents).
card: is the dependent variable. It signifies whether the application for credit card was accepted or rejected owner: is an indicator variable. it signifies whether the applicant owns a home or not.
reports: is a continuous variable. it signifies how many major derogatory reports is against the applicant age: is a continuous variable. it signifies the age of the owner plus twelfths of a year
income: is a continuous variable. it signifies the yearly income( in USD 10,000) of the applicant.
dependents: is a continuous variable. it signifies the number of dependents the applicant has.
Source:
The CreditCard dataset can be found in the AER package. Main Reference: Greene, W.H. (2003). Econo- metric Analysis, 5th edition. Upper Saddle River, NJ: Prentice Hall.
This dataset consists of Cross-Section data on the credit history for a sample of applicants for a type of credit card. The data frame contains 1,319 observations on 12 variables.
