E-Commerce-Business-Leaking-Profit

A profit-diagnosis analysis of 30,000 e-commerce orders
---------------------------------------------------------------------------------------------------------------------------------------------------


Executive Summary
This project diagnoses where profit is being lost across an e-commerce business of 30,000 orders spanning 4 years, 8 product categories, and 10 countries. Rather than reporting vanity revenue metrics, the analysis focuses on profit quality — margin, returns, discounting, and fulfilment cost — to answer a single question a real business would pay for: where are we leaking profit, and what should we do about it?

---------------------------------------------------------------------------------------------------------------------------------------------------



Headline findings:

1.	Revenue ≠ profit. Electronics drives 56% of revenue but only 47% of profit - a volume-heavy, low-margin category (16.5% margin vs. 29% for Beauty). Chasing Electronics volume is the least profit-efficient growth path.

2.	Returns concentrate in Fashion. Fashion's return rate (13.9%) runs well above the company average (10.1%), with $50K of profit tied to returned orders — the single largest returns exposure.

---------------------------------------------------------------------------------------------------------------------------------------------------

Recommendations:
•	Rebalance growth investment toward high-margin categories (Beauty, Fashion) rather than low-margin volume.
•	Launch a Fashion returns-reduction initiative (sizing guides, richer imagery, subcategory review).


---------------------------------------------------------------------------------------------------------------------------------------------------




Dataset
ecommerce_orders_dataset.xlsx — 30,000 orders × 41 columns.
Grain: one row per order. Key fields grouped by theme:
•	Order & date: Order_ID, Order_Date, Year, Month, Quarter, Season, Holiday_Season
•	Customer: Customer_ID, Customer_Age, Customer_Gender, Customer_Segment, Membership_Status, Customer_Lifetime_Value, Country, City
•	Product: Product_ID, Product_Category, Product_Subcategory, Brand, Unit_Price, Quantity
•	Pricing & profit: Discount_Percent, Discount_Amount, Coupon_Used, Tax_Amount, Shipping_Cost, Order_Amount, Profit_Margin_Percent, Profit_Amount, High_Value_Order
•	Fulfillment: Shipping_Method, Warehouse_Region, Delivery_Days, Order_Status, Returned
•	Behavioral: Payment_Method, Device_Type, Traffic_Source, Review_Rating
