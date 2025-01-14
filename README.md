# Food Delivery Cost Analysis

## Overview

This project involves analyzing the cost structure and profitability of a food delivery service. The dataset contains information about orders, delivery fees, payment methods, discounts, and various fees associated with each order. The goal is to assess the profitability of each order and understand the cost distribution.

## Dataset

The dataset consists of 1000 rows and 12 columns. The key columns include:

- **Order ID**: Unique identifier for each order.
- **Customer ID**: Unique identifier for each customer.
- **Restaurant ID**: Unique identifier for each restaurant.
- **Order Date and Time**: The timestamp when the order was placed.
- **Delivery Date and Time**: The timestamp when the order was delivered.
- **Order Value**: The total value of the order.
- **Delivery Fee**: The fee charged for delivering the order.
- **Payment Method**: The payment method used for the order (e.g., Credit Card, Digital Wallet, Cash on Delivery).
- **Discounts and Offers**: The discounts or promotional offers applied to the order.
- **Commission Fee**: The fee taken by the platform for processing the order.
- **Payment Processing Fee**: The fee for processing the payment.
- **Refunds/Chargebacks**: The amount refunded or charged back.

## Data Cleaning and Preprocessing

1. **Date Conversion**: The 'Order Date and Time' and 'Delivery Date and Time' columns were converted to datetime format for easier analysis.
2. **Discount Extraction**: The 'Discounts and Offers' column was processed to extract numerical values, and any percentage values were converted to actual amounts based on the order value.
3. **Cost Calculation**: A new column 'Costs' was created, which is the sum of Delivery Fee, Discounts and Offers, and Payment Processing Fee.
4. **Profit Calculation**: A new column 'Profit' was added, which represents the difference between the Commission Fee and the Costs.

## Key Analysis

- **Total Profit**: The total profit for the entire dataset was calculated, which showed a negative value indicating overall loss.
- **Cost Distribution**: A pie chart was created to visualize the distribution of Delivery Fee, Payment Processing Fee, and Discounts and Offers.
- **Commission vs. Costs vs. Profit**: A bar chart was created to compare the total Commission Fee, Costs, and Profit.
- **Profit Distribution**: A histogram was plotted to show the distribution of profits across all orders.

## Visualizations

1. **Cost Distribution**: A pie chart showing the relative contributions of Delivery Fee, Payment Processing Fee, and Discounts and Offers to the total costs.
2. **Commission, Costs, and Profit Comparison**: A bar chart comparing the total values of Commission Fee, Costs, and Profit.
3. **Profit Distribution**: A histogram displaying the spread of profits across orders.
