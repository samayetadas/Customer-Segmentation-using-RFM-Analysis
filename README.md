# Customer-Segmentation-using-RFM-Analysis

Using a dataset that contains sales orders in a period of time, we used Python to obtain the frequency, recency, and monetary values in the last 365 days per customer. Later with those values gave R, F, and M scores to each customer, which allowed us to cluster them in different segments.

### RFM is a method used for analyzing customer value. It is commonly used in database marketing and direct marketing and has received particular attention in retail and professional services industries.
* Recency is the minimum of 'days_since_last_purchase' for each customer.
* Frequency is the total number of orders in the period for each customer.
* Monetary is the total value of the purchases in the period for each customer

We focused on sales from last 365 days since the most recent date.

The Data was obtained from real sales orders in 18 countries in a period of around 2 years. Some features (country names, customer id and revenue), were altered in order to preserve privacy. Number of orders, units and dates were not modified.The data has been attached with the repository.

# Customer Segment description
* Champions Bought recently, buy often and spend the most
* Loyal Customers Buy on a regular basis. Responsive to promotions.
* Potential Loyalists Recent customers with average frequency.
* Recent Customers Bought most recently, but not often.
* Promising Recent shoppers, but haven’t spent much.
* Customers Needing Attention Above average recency, frequency and monetary values. May not have bought very recently though.
* About To Sleep Below average recency and frequency. Will lose them if not reactivated.
* At Risk Purchased often but a long time ago. Need to bring them back!
* Can’t Lose Them Used to purchase frequently but haven’t returned for a long time.
* Hibernating Last purchase was long back and low number of orders.
* Lost Purchased long time ago and never came back.

Please refer to the PowerBI file for the visualizations and plots
