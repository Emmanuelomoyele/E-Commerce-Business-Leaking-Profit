E-Commerce-Business-Leaking-Profit

A profit-diagnosis analysis of 30,000 e-commerce orders
--------------------------------------------------------------------------------------------------------------


Executive Summary
                                                
This project looks at 30,000 online orders over 4 years.
It covers 8 types of products and 10 countries.
Instead of just looking at total sales which can look good but don't tell the full story this analysis focuses on what really matters for profit:
•	Profit margins (how much is left after costs),
•	Returns,
•	Discounts given to customers, and
•	Shipping and handling costs.

The goal is to answer one important question that any real business would ask:
Where are we losing profit, and what can we do to fix it?
--------------------------------------------------------------------------------------------------------------



Headline findings:

1.	Revenue ≠ profit (Revenue is not the same as profit)
Electronics makes up 56% of all sales, but only 47% of all profit.
That means it sells a lot but earns less per item its profit margin is 16.5%, while Beauty’s is 29%.
So, trying to grow by selling more Electronics is the worst way to increase profits.

2.	Fashion has the most returns.
Its return rate is 13.9%, which is much higher than the company average of 10.1%.
Returns on Fashion orders cost the company $50,000 in lost profit.
This is the biggest returns problem the company has.

--------------------------------------------------------------------------------------------------------------

Recommendations:

•	 Put more money and effort into growing categories that make higher profit per sale, like Beauty and Fashion, instead of chasing big sales numbers in low-profit categories like Electronics.
•	Start a plan to cut down on Fashion returns by:
i)	adding better size guides,
ii)	using more detailed product photos,
iii)	and checking which specific Fashion items are returned most often.


-------------------------------------------------------------------------------------------------------------




                                                Dataset
ecommerce_orders_dataset.xlsx — 30,000 orders × 41 columns.
Grain: one row per order. Key fields grouped by theme:
•	Order & date: Order_ID, Order_Date, Year, Month, Quarter, Season, Holiday_Season
•	Customer: Customer_ID, Customer_Age, Customer_Gender, Customer_Segment, Membership_Status, Customer_Lifetime_Value, Country, City
•	Product: Product_ID, Product_Category, Product_Subcategory, Brand, Unit_Price, Quantity
•	Pricing & profit: Discount_Percent, Discount_Amount, Coupon_Used, Tax_Amount, Shipping_Cost, Order_Amount, Profit_Margin_Percent, Profit_Amount, High_Value_Order
•	Fulfillment: Shipping_Method, Warehouse_Region, Delivery_Days, Order_Status, Returned
•	Behavioral: Payment_Method, Device_Type, Traffic_Source, Review_Rating
