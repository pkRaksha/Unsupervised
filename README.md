# Unsupervised
## Project Summary -
The aim of the project is to segment the online retail customers based the RFM model (Recency,Frequency and Monetory) and identify the customer groups who play a major role in increasing the profits in online retails and the rest of the customers who are still getting aquinted with online shopping . Based on this clustering we can target each group of customers and give offers,discounts and ads to improve the business in a positive way . Through exploratory analysis and model building the above insights are achieved The models used for clustering are :

K -means clustering (Silhouette, elbow method,dbscan)
Hierarchical clustering (Dendrons)

## Data Description
Attribute Information:
InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.
## Conclusion
This project mainly focused on developing customer segments for a UK based online store, selling unique all occasion gifts.
Using a recency, frequency and monetary(RFM) analysis, the customers have been segmented into various clusters and got a silhoutte score of 0.39 for two clusters
By applying different clustering algorithm to our dataset, we get the optimal number of cluster is equal to 2.

The business can focus on these different clusters and provide customer with services of each sector in a different way, which would not only benefit the customers but also the business at large.
