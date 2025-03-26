# LR_Delivery_Time_Prediction
Objective
This assignment will help you apply linear regression techniques to a real-world business scenario.
By working through this exercise, you will gain hands-on experience in using regression analysis to
identify key relationships between variables, make data-driven predictions and extract actionable
business insights. You will also develop an understanding of how to interpret regression outputs,
assess model performance and effectively communicate findings to support strategic decision-making.
Business Value
The growing demand for quick and efficient delivery in the logistics industry calls for the development
of systems that can predict delivery times accurately. Porter, an intra-city logistics marketplace,
services millions of customers daily, and optimising delivery times is crucial for improving operational
efficiency.
The objective is to build a linear regression model that can perform the following:
1. Predict the delivery time for an order based on various input features.
2. Help optimise delivery operations by providing accurate time estimates.
3. Support operational planning and resource management, allowing for more effective use of
delivery partners.
Dataset Overview
Context
The Porter Parcel Delivery Times data set provides details about orders placed through Porter. The
data has information about the orders, such as item quantity and order amount; information about
the store, such as category, distance from customer and market ID; and operational information,
such as the number of delivery partners.
Content
The dataset consists of multiple observations, each representing data for a specific order, with the
following key attributes:
Column Name Description
market_id ID of the market where the restaurant is located.
created_at The timestamp when the order was placed.
actual_delivery_time The timestamp when the order was delivered.
store_primary_category The category of the restaurant (e.g., fast food or dine-in).
order_protocol The integer code indicating how the order was placed (e.g., via
Porter or call to restaurant).
total_items The total number of items in the order.
subtotal The total price of the order.
num_distinct_items The number of distinct items in the order.
min_item_price The price of the cheapest item in the order.
max_item_price The price of the most expensive item in the order.
iLinear Regression Assignment:
Parcel Delivery Time Estimation
Assignment ID: LR/02
Total Marks: 100
total_onshift_dashers The number of delivery partners on duty at the time the order
was placed.
total_busy_dashers The number of delivery partners already attending to other tasks.
total_outstanding_orders The number of outstanding orders to be fulfilled at the time the
order was placed.
distance The total distance from the restaurant to the customer.
