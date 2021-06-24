# Retail-Sector-Domain-Analysis
**Business Problem:**
 For a medium to large size retail store, it is also imperative that they invest not only in acquiring new customers but also in customer retention. Many businesses get most of their revenue from their ‘best’ or high-valued customers. Since the resources that a company has, are limited, it is vital to find these customers and target them to win customer loyalty, drive business efficiencies and ultimately improve performance.

**Objective**
To predict for all customers who shopped at-least once during 12/1/2009 till 11/9/2011.

To Predict who will come back to buy any product next month (11/9/2011 – 12/9/2011).

To predict likelihood of customers shopping next month

**Variables**
The variable names and their descriptions are as follows:

InvoiceNo: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.

StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.

Description: Product (item) name. Nominal.

Quantity: The quantities of each product (item) per transaction. Numeric.

InvoiceDate: Invoice Date and time. Numeric, the day and time when each transaction was generated.

UnitPrice: Unit price. Numeric, Product price per unit in sterling.

CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.

Country: Country name. Nominal, the name of the country where each customer resides.
**
**Method****
i)Customer Clustering
ii)ML model

Conclusion
We are able to separate customers into different segments, based on the type of products that they buy.
we can  conclude that XGBoost model has little more accuracy compared to other models.
We can use this information to target selected customers with promotional offers for their desired products, which increases the likelihood of more sales in the future.
