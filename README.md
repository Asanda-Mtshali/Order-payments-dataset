# Order Payment Dataset Analysis

## Project Overview
This project analyzes an **order payment dataset** to uncover insights about customer payment behavior, revenue generation, and payment trends. It demonstrates the use of **SQL aggregation, grouping, and filtering** to produce meaningful business insights.

## Dataset Description
- **Table Name:** order_payment_dataset
- **Key Columns:**
  - `order_id`: Unique identifier for each order
  - `payment_value`: Value of a single payment
  - `payment_installments`: Number of installments for the payment
  - `payment_type`: Payment method (e.g., credit card, voucher, cash)
  - `payment_sequential`: Sequential number of the payment in an order

## Analysis Performed
1. **Total Revenue:** Calculates the total revenue from all orders.  
2. **Revenue Excluding Credit Cards:** Calculates revenue from payment types other than credit cards.  
3. **Number of Credit Card Payments:** Counts how many payments were made using credit cards.  
4. **Distinct Payment Types:** Lists all different payment methods used by customers.  
5. **Average Number of Payments per Order:** Calculates the typical number of payments made for each order.  
6. **Top Payment Methods:** Identifies the most frequently used payment methods.  
7. **Revenue per Payment Type:** Shows which payment methods contribute most to revenue.

## Insights / Key Findings
- The majority of orders are **single-payment orders**.  
- Credit cards are commonly used, but revenue contributions vary by payment type.  
- Multiple payment methods per order are rare but can be important for customer behavior analysis.  
- Businesses can focus on the **most popular payment types** to optimize payment processing.

## Skills Demonstrated
- SQL **aggregation functions** (`SUM`, `COUNT`, `AVG`)  
- SQL **filtering** (`WHERE`, `NOT`, `!=`)  
- SQL **grouping and subqueries** (`GROUP BY`, subqueries for averages)  
- Data analysis mindset for **revenue and customer behavior insights**

## How to Run
1. Clone the repository.  
2. Load the `order_payment_dataset` into your SQL environment (e.g., SQL Server, MySQL, or PostgreSQL).  
3. Run 
