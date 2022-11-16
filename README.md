# Customer Churn Data Business Analysis

Dataset from [Maven Analytics](https://www.mavenanalytics.io/data-playground)

**Scenario**
As a data analyst for a fictional Telecommunications company that provides phone and internet services to 7,043 customers in California, using the data provided which includes details about customer demographics, location, services, and current status to analyze their customers churn last quarter

## Questions
1. How many customers joined the company during the last quarter?
2. What is the customer profile for a customer that churned, joined, and stayed? Are they different?
3. What seem to be the key drivers of customer churn?
4. Is the company losing high value customers? If so, how can they retain them?


![image](https://user-images.githubusercontent.com/104981673/201560783-488ffa39-3721-4ac9-8baa-4498e9b59b30.png)

 [code](https://github.com/atriap/Customer-Churn-Data-Analysis/blob/main/Customer%20Churn%20Analysis.ipynb)

## Conclusion

- Customers who churned in this quarter are 1,869 people (26.54%) among 7,043 customers. The company has gained 454 (6.45%) new customers this quarter
- Based on the analysis, it can be seen that there are characteristics of 3 customer groups, namely churned customers (overall), high value customers, and just joined customers
    - **Churned customers** are those who have just joined for a short time, choose a month to month contract, and have a high monthly charge. Overall the proportions of men and women are the same over a wide age range. Using a month to month contract, it will be easier to churn because it is easier to end the contract the next month.
    - **High value customers** are those who generate higher than average revenue gained, generally they choose many types of services--ranging from telephone, internet, streaming services on various platforms. Those who do churn are the elderly and men. This can be affected by income (e.g. due to retirement and choosing cheaper competitors to save money)
    - **Joined customers** are those who are interested in joining because of low-cost telephone services--even if they use the internet service they use mobile phones instead of using wires, mostly young people, prefer to pay via credit card (this can also be assumed that there is an ongoing collaboration promo)
-  Customers who are staying mostly are the ones with yearly contract and have lower monthly charge
-  Customers who generate minimum revenue are more likely to churn. Although their monthly fee is high, but they only join for a short time


## Recommendation

- Company can provide interesting offers especially for customers who use month-to-month contracts, for example with bonus quota or credit for each renewal in a certain nominal so that they retain and are interested in continuing to use the service
- Improving internet services using **fiber optic** due to the high number of churn users of the service
- The biggest reason for churn is due to competitors, therefore a more in-depth analysis is needed by the marketing team, such as benchmarking to competitors regarding service quality and price / offers
- The biggest reason besides competitors is attitude, therefore companies should conduct training and recruit employees who really understand their products and have good attitude



more detailed analysis in the Jupyter Notebook [code](https://github.com/atriap/Customer-Churn-Data-Analysis/blob/main/Customer%20Churn%20Analysis.ipynb). 
