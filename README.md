Telco_churn

Problem Statement

With increase in number of telecommunication operators a customer is entitled with unlimited freedom to switch from one mobile operator to another, if he is not satisfied with the services or pricing their providers are providing. This trend is not good for operators as they lose their revenues because of customers switching from one provider to another in search of cheap affordable high-quality products and services [1]. The rate at which you are losing subscribers or customer is called 'churn rate'

Data Science Problem Statement

Analyse customer-level data, build predictive models to identify customers at high risk of churn and identify the main indicators of churn. most telecom service providers lack personilized way of recommending products and services to the subscribers and most of them do not have tactics to reduce chun. Increase in churn rate will result in revenue shrinkage for the company.

Business Goals

Segment based on usage and identify the high value customers
if we can reduce churn of the high-value customers, we will be able to reduce significant revenue leakage.
business objective is to predict the churn in the last (i.e. the ninth) month using the data (features) from the first three months. To do this task well, understanding the typical customer behaviour during churn will be helpful.
Before starting to work recommendations, Customer segmentation is very important.

About Data

As this data is mostly indian and southeast Asia,prepaid is the most common plan in used. Focus on prepaid customers.
Class imbalance
Churn definition used-- "Usage-based churn: Customers who have not done any usage, either incoming or outgoing - in terms of calls, internet etc. over a period of time." In this project, we will use the usage-based definition to define churn.
In this project, you will define high-value customers based on a certain metric (mentioned later below) and predict churn only on high-value customers.
especially high-value customers go through three phases of customer lifecycle: a. The ‘good’ phase, b. The ‘action’ phase, c. The ‘churn’ phase

Approach:
For given unbalanced data build Telecom Churn Model:
