# Instacart-Data-Wrangling
Instacart is a grocery delivery platform where customers can register an order and have it delivered to their home.

The objective of this project is to clean the data and prepare a report that provides information about the purchasing habits of Instacart customers, that is, perform pre-processing and exploratory analysis of the data.

Throughout the work, graphics will be created to communicate the results through the matplotlib.pyplot library.

# Data Description:
Below is a data dictionary listing the columns of each table and describing the data they contain.

### instacart_orders.csv
Each row corresponds to an order in the Instacart application.
- ***'order_id'***: ID number uniquely identifying each order.
- ***'user_id'***: ID number uniquely identifying each customer's account.
- ***'order_number'***: the number of times this customer has placed an order.
- ***'order_dow'***: the day of the week the order was placed (0 if Sunday).
- ***'order_hour_of_day'***: the hour of the day the order was placed.
- ***'days_since_prior_order'***: number of days elapsed since this customer's previous order.

### products.csv
Each row corresponds to a unique product that customers can buy.
- ***'product_id'***: ID number uniquely identifying each product.
- ***'product_name'***: name of the product.
- ***'aisle_id'***: ID number uniquely identifying each grocery aisle category.
- ***'department_id'***: ID number uniquely identifying each grocery department.
### order_products.csv
Each row corresponds to an item ordered in an order.
- ***'order_id'***: ID number uniquely identifying each order.
- ***'product_id'***: ID number uniquely identifying each product.
- ***'add_to_cart_order'***: the sequential order in which each item was added to the cart.
- ***'reordered'***: 0 if the customer has never ordered this product before, 1 if they have.

### aisles.csv
- ***'aisle_id'***: ID number uniquely identifying each grocery aisle category.
- ***'aisle'***: name of the aisle.

### departments.csv
- ***'department_id'***: ID number uniquely identifying each grocery department.
- ***'department'***: name of the department.