# RFM-Analysis

## What is RFM Analysis?
RFM **(Recency, Frequency, Monetary)** analysis is a proven marketing model for behavior based customer segmentation. It groups customers based on their transaction history – how recently, how often and how much did they buy.

RFM helps divide customers into various categories or clusters to identify customers who are more likely to respond to promotions and also for future personalization services.

## 1. Descriptive Analysis
Descriptive analytics is a statistical interpretation used to analyze historical data to identify patterns and relationships.

The dataset was cleaned using pandas and numpy, followed by segmentation analysis based on RFM score to group customers. Data visualization and insights were obtained using matplotlib and seaborn. Appropriate solutions were suggested for each customer group based on their characteristics.

### Result:
<img src="https://github.com/khlinh2512/RFM-Analysis/assets/118649367/8e35ef4d-558f-4662-a69d-cbb66c473c73" width = "410" height= "410" /><img src="https://github.com/khlinh2512/RFM-Analysis/assets/118649367/3907a419-6505-42dc-a15d-31a04d86c208" width = "410" height= "410" />
<img src="https://github.com/khlinh2512/RFM-Analysis/assets/118649367/1fafc34e-c755-4cff-a0e5-0f68869a5994" width = "450" height= "410" /><img src="https://github.com/khlinh2512/RFM-Analysis/assets/118649367/209e5c19-b0e0-44a4-afea-4abc1d466e3d" width = "400" height= "410" />

### Findings:
Identify customer groups that need to be focused on to develop appropriate strategies (using the 80/20 rule)

* The **most customers** groups are: **New Customer, At risk**
Meanwhile, the two most important customer segments that are predicted to bring the largest revenue and profit are Champions and Loyal Customers, but they only account for a small portion of customers. That aligns with the "80/20 rule" - that "80% of a company's revenue comes from 20% of its customers."

* The **most recency** buyer groups are: **Champions, Potential Loyalist, Promising, New Customer, Need Attention and Loyal**

* The **most frequent** buyer groups are: **Champion, Loyal, Cannot Lose Them, At risk**
To increase retention rates, pay more attention to the Potential Loyalist and About to Sleep groups.

* The groups that spend the **most money** are: **Champion, Loyal, Cannot Lose Them, At risk**
The Cannot Lose Them and At risk groups used to buy regularly but have not done so for a long time -> Need additional solutions to retain these customers.

***With the criteria***:
* A cost of business is 5 times more to attract a new customer than to retain the existing ones.
* 20% of customer contributing to 80% of total revenues
* Therefore, special attention should be paid to customer segments that generate high and frequent revenue.

## 2. Predictive Analysis
I finished the prediction code in my other project: Predicting_Customer_Segment
