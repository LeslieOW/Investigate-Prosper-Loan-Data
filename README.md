## Loan Data Exploration


### By Leslie Wagwa


### Dataset
Prosper loan dataset comprises of information about loans awarded by Prosper to their clients. The dataset is made up of 113,937 features. 

### Summary of findings

#### > Univariate exploration
My interest on this dataset is to figure out which features the firm should put more emphasis on when awarding loans to their clients so as to minimize the rate of default and maximize profitability.
The main features in the dataset that would be of help in my analysis are; occupation, employment status, is borrowerhomeowner, debt-to-income ratio, original loan amount and loan status.

Among the key observations are:
  i)A vast majority of the borrowers are employed. This is logicall as it would be difficult for an unemployed individual to be given a loan which translates to difficulty in servicing the loan.
  ii)The largest loan amount that was given by Prosper to its borrowers is 4k. However, we can also see the second and third largest loan amount to be 15k and 10k respectively.
  
#### > Bivariate exploration
In this phase of my analysis, i focused on determining relationship between pairs of the features of the data.
I noticed that there is a very high correlation between OpenRevolvingAccounts and CurrentCreditLines.On the flip side, the other variables were either barely correlated or had no correlation at all.
I also realized from my findinds that the BorrowerAPR for unemployed individuals is slightly higher than the rest since they have a higher risk of default.
Another observation made was that, as expected, individuals who are employed are awarded a large loan amount. This is simply because they have a regular sourse of income and are therefore able to service their loans with ease as compared to those who were not employed.

#### > Multivariate exploration
Focusing on multiple variables of the data,  I observed that the borrower rate charged on loans offered by Prosper is dependent on the loan amount.A larger loan amount attracts a smaller rate and there is an inverse relationship.
A key insight I gained during my analysis is that borrower rates charged by Prosper are based on whether the borrower owns a home or not and their employement status. Owning a home serves as a collateral to the loan taken. Individuals without homes are charged a higher rate because they do not have homes to be used as collateral.

Employment is also a factor considered when charging rates on loans. Because unemployed individuals lack regular income to service their loan, they are charged higher rates as compared to their peers as they have a higher risk of defaulting.

### Key insights for Presentation
I focused mainly on features the firm should put more emphasis on when awarding loans to their clients so as to minimize the rate of default and maximize profitability.
My presentation focuses on the features discussed above but now in a visual context.


```python

```
