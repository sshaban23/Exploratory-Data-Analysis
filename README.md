# Exploratory-Data-Analysis

A1: QUESTION FOR ANALYSIS: 

Is there a difference in monthly charges between customers that Churn or do not churn?


A2: BENEFIT FROM ANALYSIS:

The benefit of this analysis is that it helps us understand if there's a meaningful difference in the average monthly charges between customers who churn and those who don't. By knowing this difference, a company can make informed decisions. If churned customers have significantly higher or lower monthly charges, the company could adjust its pricing strategies or customer retention efforts accordingly. This analysis provides valuable insights for improving customer satisfaction and reducing churn, which leads to better business outcomes.

A3: DATA IDENTIFICATION:

    1-	Churn (yes/no)

    2-	MonthlyCharge ($#) Exmple: $172.45


B2: OUTPUT:

    T-statistic: 40.18947672237426

    P-value: 0.0


B3: JUSTIFICATION:

I chose the t-test because it's good for comparing the average monthly charges between two groups: customers who churn and those who don't. Since "Churn" is a yes/no variable and "MonthlyCharge" is a number, the t-test helps me see if there's a real difference between the two groups. It gives clear results, showing if the difference we see is likely real or just by coincidence.


C: UNIVARIATE STATISTICS:

Two continuous variables: ‘Income’ and ‘MonthlyCharge’
Two categorical variables: ‘Churn’ and ‘Techie’

Income variable's distributions: the distribution is right skewed which shows that more people have lower incomes rather than higher income.

MonthlyCharge variable's distributions: the distribution is symmetrical which shows us that the monthly charges are average.

Churn variable's distributions: the distribution of the bar chart us uneven with more customers not churning rather than churning.

Techie variable's distributions: the distribution of the bars in the bar chart are uneven with more customers being not technically savvy as compared to the ones that are.

C1: VISUAL OF FINDINGS:

![image](https://github.com/user-attachments/assets/de7b9199-9545-48a2-b929-7174dcf28da0)

![image](https://github.com/user-attachments/assets/9a796562-deb7-416e-9144-03c2b7b50247)

![image](https://github.com/user-attachments/assets/dc55a58e-30ee-406c-9a3e-2074031ac4b0)

![image](https://github.com/user-attachments/assets/c23f6892-b7ac-401a-86a6-8adeeeb17cf1)


D: BIVARIATE STATISTICS:

Two continuous variables: ‘Outage_sec_perweek’ and ‘Tenure’

Two categorical variables: ‘OnlineSecurity’ and ‘TechSupport’


Correlation analysis for continuous variables: The correlation shows a weak correlation which tells us that maybe other variables have more of an effect on outage times.

Chi-Square Test for categorical variables: The graphs show us that online security and tech support are important variables that reduce the churn rate.

Boxplots: After examining all the results of the boxplots, I found that online security and tech support lead to fewer outages and longer customer tenures.

Scatter Plot: the scatter plot shows that tenure is not strongly related to outage times.


D1: VISUAL OF FINDINGS:

![image](https://github.com/user-attachments/assets/5cc5376f-5362-4c72-9276-53dcf5403e22)

![image](https://github.com/user-attachments/assets/025800c1-1a91-4684-94d3-c5d59536381f)

![image](https://github.com/user-attachments/assets/486dd0f1-fbbb-48b1-86f6-29206d892464)

![image](https://github.com/user-attachments/assets/3ce857ca-5920-4c65-a25b-9e61b7b924ad)

![image](https://github.com/user-attachments/assets/d5451f0f-c797-4de5-beee-6f28e7f378cc)

![image](https://github.com/user-attachments/assets/75634f19-c145-4ccf-a193-28dfc31b0279)

![image](https://github.com/user-attachments/assets/4ea486dc-df9f-4841-9039-5a816bfd1adb)

![image](https://github.com/user-attachments/assets/0f4076b5-20c2-46f8-b1dd-0fa704d6db04)


E1: RESULTS OF ANALYSIS:

The analysis showed how important good online security and tech support are for keeping customers. Since these services are linked to lower churn rates, the company should focus on improving the services to make the customers happier and more loyal. Also, I found that higher monthly charges are linked to higher churn rates which means we need to review and adjust our prices to avoid losing customers. I believe by enhancing the company’s online security and tech support, and making sure their prices are fair and competitive, the company can keep more customers satisfied and loyal which will reduce the churn rate. 


E2: LIMITATIONS OF ANALYSIS:

Some limitations are that the data we used might not be perfect, and there could be missing information. We only looked at a few specific things, but there could be other important factors we didn't consider. Also, our analysis made some assumptions that might not always be true. And even though we found some important results, what we found might not always have a big impact in real life. So, while the analysis helped us understand some things, we should keep these limitations in mind when thinking about the results.


E3: RECOMMENDED COURSE OF ACTION:

Based on what I found, it's important to take action to deal with the big difference I saw in how much customers pay each month between those who stay and those who churn. One thing the company could do is talk to customers to understand why they might feel differently about the price or what they get for it. Then, we could think about adjusting our prices to match what customers expect and what other companies are doing. It might also help to focus on keeping customers happy and coming back by offering them special deals or improving our service. By doing these things, we can hopefully keep more customers around and make our business better in the long run.

