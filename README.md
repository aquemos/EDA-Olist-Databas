# EDA-Olist-Database

This project conduct exploratory data analysis on the Olist e-commerce database, focusing on four main objectives:

1. The company aims to identify the most frequently ordered product categories on Olist.
2. The company intends to examine the sales trends within the product categories identified in the previous objective.
3. Furthermore, the company seeks to analyze the distribution of order statuses across different years within the most frequently ordered product categories mentioned in objective 1.
4. Lastly, given the occurrence of several orders that were shipped in 2017 and 2018 but lack information on the date of receipt by customers, the company aims to determine if shipping delays are prevalent in specific locations for these product categories.

From the exploration above, several information are obtained:

* The "bed_bath_table" product category has been the top-selling product from 2016 to 2018.

* Sales trends for "bed_bath_table" products are increase year over year.

* Orders from 2016 were successfully fulfilled. However, some orders from 2017 and 2018 are still in the "invoiced", "shipped", and "processing" status. This suggests a possibility that these orders may not have reached the customers. Additionally, there is one "delivered" order from 2017 that does not have a payment date.

* Among the "bed_bath_table" category orders from 2017 and 2018 with a "shipped" status, cross-country shipments dominate the orders without a confirmed delivery date. Most of these orders are originating from Ibitinga city, SP state, heading to Rio De Janeiro city, RJ state. Orders with a "shipped" status lacking shipment dates within the same country are mostly from Ibitinga city to Sao Paulo city.

Based on the information obtained, there are several actions that the company can consider:

* Ensure that orders marked as "invoiced", "shipped", and "processing" in 2017 and 2018 have reached the customers or investigate the reasons for delays.

* Specifically, pay attention to the shipping issues (orders with "shipped" status) from Ibitinga to Rio De Janeiro. Improving the cross-country shipping process may be necessary, including checking for customs or logistics problems causing delays. It may also be beneficial to evaluate shipping policies, costs, and options to enhance efficiency and customer satisfaction.

* Confirm payments for the "delivered" order from 2017 that does not have a payment date. Ensure that the payment system is functioning properly and extend efforts to reach out to customers who haven't made payments.

* By taking these steps, the company can enhance its operations, address potential delivery and payment issues, and improve overall customer satisfaction.

The Indonesian article about this project can be accessed [here](https://medium.com/@novitasariarlim/analisis-olist-e-commerce-data-wrangling-dan-sql-5ef7456e314b).
