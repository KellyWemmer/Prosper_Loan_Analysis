
# Prosper Loan Data Exploration

## By Kelly Wemmer

### Dataset

This dataset includes 113937 different loans and 81 variables describing credit scores, APR, employment status, among other information. After cleaning the data, I filtered the dataset down to 77557 loans that included the relevant information to run my analyses. 

<br>With this dataset, I analyzed credit score, debt to income ratio, prosper rating (Alpha), the term of loan, homeownership, income range and compared them to Annual Percentage Rate.


The data can be downloaded at https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv 
<br> The dataset feature documentation can be viewed at https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

### Summary of Findings


The Prosper rating had a high correlation with the borrowers' APR. When analyzing the bivariate data, the better Prosper rating corresponded to the lower APR. 


When analyzing the Prosper Rating's effect on Debt to Income Ratio and APR, there was a positive correlation starting with the "AA" and "A" ratings, then continued to zero and negative correlations as the Prosper ratings decreased.


The bivariate chart depicting credit score vs APR shows a negative correlation, with the lower credit score having a higher APR. 


When analyzing the mean credit score with Prosper ratings and APR, the higher prosper ratings ("AA" and "A") had a slightly negative correlation with mean credit score, but continued to zero and positive correlations as Prosper ratings declined. In other words, when a borrower has a high Prosper rating, the APR decreases as credit score increases, but as Prosper ratings decrease, the APR increases or has zero effect on APR as credit score increases.

Income range also had an impact on borrower APR. As the income range increased, the borrower APR decreased. 


When analyzing homeownership vs APR, homeowners in the 1-24,999 income range had a higher APR than non-homeowners. This changed when income range reached 25,000, and homeownership had a lower APR than non-homeowners.

### Key Insights for Presentation

From the analyses of this dataset, Prosper rating and credit score seem to have a high influence on the borrower APR. Income range and debt to income ratio also have a correlation with APR, but these were not as significant as the Prosper ratings and credit score. Homeownership had some correlation to borrower APR, but not as significantly as the above mentioned features.  


```python

```
