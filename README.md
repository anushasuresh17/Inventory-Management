Project Overview
This project focuses on inventory management for optimizing product availability while minimizing costs. Key techniques such as demand forecasting, safety stock calculation, reorder point determination, Economic Order Quantity (EOQ), and ABC analysis are applied to manage inventory for different products.

Data
The dataset used in this project contains the following columns:

Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Customer Name, Segment, Country, City, State, Postal Code, Region, Product ID, Category, Sub-Category, Product Name, Sales, Quantity, Discount, Profit, Order Year, Order Month, Order Weekday, Shipping Lead Time
Key Features Extracted:
Order Year, Month, Weekday: Extracted from Order Date for time series analysis.

Shipping Lead Time: Calculated as the difference between Ship Date and Order Date.
Key Techniques Applied
1. Demand Forecasting
Used Exponential Smoothing to forecast product demand based on monthly sales data.
Visualized sales trends and forecast for a specific product.
2. Safety Stock & Reorder Point Calculation
Safety stock calculated using a 95% service level to prevent stockouts.
Reorder point calculated considering average demand and lead time, ensuring timely reordering.
3. Economic Order Quantity (EOQ)
EOQ formula applied to determine the optimal order quantity that minimizes ordering and holding costs for a product.
4. ABC Analysis
Categorized products based on their contribution to total sales:
A category: Top 20% of products contributing 80% of revenue.
B and C categories: Lesser revenue contributions.
Visualized the classification to guide inventory prioritization.

Results
Safety Stock: 357.91 units for the selected product.
Reorder Point: 492.43 units for timely reordering.
EOQ: 11.72 units, indicating the optimal order size for minimizing costs.
ABC Analysis: Identified top-performing products that require stricter inventory control.
