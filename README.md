# Analyzing eCommerce Business Performance with SQL
- Analyze three aspects related to the company's business performance.
- These three aspects include **Customer Growth**, **Product Quality** and **Payment Types.**
- This dataset is obtained from [Rakamin Academy](https://www.rakamin.com/)

# Purpose
Create a **Business Performance Report** on these three aspects.

# Data Analysis
1. Entity Relationship Diagram (ERD)
![ERD](/Image/ERD%20Mini%20Project.png)

2. Customer Growth
![Customer Growth](/Image/Customer%20Growth.png)
    - Monthly Active Users increase every year. The biggest increase occurred in 2017 with a value of 3695 users or 3586 higher than the previous year.
    - New customers increase every year. This increase is proportional to the number of Monthly Active Users. This proves that the majority of active users are new customers.
    - Customers who made repeat orders increased sharply in 2017 with a value of 1256 customers or 1253 higher than the previous year. However, in 2018 the number of customers who made repeat orders decreased by 89.
    - The average order frequency per year is only once. This means that most customers order only once throughout the year.
    <br>

3. Product Quality
![ProductaQuality](/Image/Product%20Quality.png)
    - Revenue increases every year. The biggest increase occurred in 2017 due to the large number of new customers and the number of customers who made repeat orders.
    - The top categories that generate the most revenue are furniture_decor (2016), bed_bath_table (2017) and health_beuty (2018).
    - The number of Cancel Orders increases every year. The biggest increase occurred in 2017 but is still within a reasonable range when compared to the number of orders received.
    - The top categories that experienced the most Cancel Order were toys (2016), sports_leisure (2017) and health_beuty (2018).
    <br>

4. Payment Types
![Payment Types](/Image/Payment%20Types.png)
    - The amount of usage for each payment_type always increases every year except for voucher types. Payments using vouchers decreased in 2018.
    - In 2018 there were also 3x payments using a type that was not defined.
    - Credit Card is the favorite type of payment. And Debit Card is the type of payment that is less attractive to customers.

# Business Insight & Recomendations
- The preferred payment method is a credit card, so that further analysis can be carried out regarding customers' habits in using credit cards.
- The type of payment by debit card increased by more than 100% from 2017 to 2018. On the other hand, vouchers actually decreased from 2017 to 2018. This may have occurred due to promotions/cooperation with certain debit cards and also a reduction in promotional methods using vouchers.
- In 2018 also found for the first time 3 Undefined Payments.