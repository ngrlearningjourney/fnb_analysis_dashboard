# Food and Beverage Business Analysis

### Dataset Explanation
- `order_id` : Synthetic order identifier. This value is intentionally not unique, allowing multiple products to belong to the same order (bridge table / order-item structure).
- `product_name` : Generic fictional food or beverage product name.
- `order_date` : Date and time when the order was placed.
- `order_type` : Order fulfillment method (Takeaway, Dine-In, or Online).
- `payment_method` : Payment method used for the transaction.
- `rating` : Customer rating for the ordered product (1–5).
- `price` : Selling price per unit of the product.
- `region` : Fictional business region where the order originated.
- `preparation_time_minutes` : Time taken to prepare the product, in minutes.
- `quantity` : Number of units ordered for the product.
- `line_total` : Total amount for the order line (price × quantity).
- `employee_id` : Synthetic identifier for the employee who prepared or handled the order.

## Metrics

The dashboard and analysis focusing on Head Of Product and Head of Operation to examine their FnB Business overtime.

- Waiting time
- Rating
- Order
- Revenue

---

## Insights

### Preparation Time
- All of our restaurant have a similar average preparation time, ranging from 23 to 24 minutes.
- At West restaurant, burgers (dine-in and online) and fries (pickup) take the longest time to prepare on average.
- At East restaurant, Cake (takeaway), sandwich (takeaway) and Burger (online) take the longest time to prepare on average.
- At North restaurant, Wrap (Online), Rice Bowl (Online) and Salad (Dine-in) take the longest time to prepare on average.
- At South restaurant, Pasta (Dine-in), Latte (Online) and Smoothie (Online) take the longest time to prepare on average.
- Lastly, at our South restaurant, Pizza (Online), Smoothie (Online) and Burger (Dine-in) take the longest time to prepare on average.

### Rating
- According to the analysis, we understand that second, fourth, fifth months have the lowest rating in this datasets, ranging from 2.9 - 3
- On the second month our restaurant in north, south, and west region have the lowest rating. It range around 2 - 3
- on forth month our restaurant in north, west, east region have the lowest rating. It range around 2.6 - 2.9
- on fifth month our restaurant in north, south, and central region have the lowest rating. They range around 2.7 - 3

  
- Overall, our restaurant in east, north, and west have the lowest rating from 5 of our restaurant. their rating raging from 2.9 - 3.1
- if we focus on our restaurant in east, the lowest rating come from their fries, followed by latte and coffe.
- And for the second lowest rating is our restaurant in North, the lowest rating come from our Pizza, followed by latte and smoothie.
- And for the last lowest rating, is our restaurant in West, the lowest rating come from our Noodle, followed by Coffe and Rice Bowl.

### Order Type
- Customers in the North region prefer to dine in at our store.
- Customers in the West and South regions prefer to place online orders.
- For takeaway orders, customers prefer the South restaurant.
- the top-selling items at our Central restaurant are wraps, rice bowls, and coffee.
- the top-selling items at our East restaurant are Latte, Pizza, and Smoothie.
- the top-selling items at our South restaurant are Latte, Tea, and Salad.
- the top-selling items at our East restaurant are Latte, Sandwich, and Fries.
- the top-selling items at our North restaurant are tea, cake, smoothie.


### Payment Method
- Based on the data, customers at the Central restaurant prefer to pay for their food using e-wallets (72 orders). However, at our other restaurants (East, North, South, and West), customers prefer to pay with cash (around 74 - 76 orders).

### Revenue
- According to the data, the restaurant generated the highest revenue in April (11k), June(11k), and May(11k), while the lowest revenue was recorded in March (9k).

### Number of Order
- According to the data, May and April had the highest number of orders compared to the other months, with 180 and 173 orders, respectively.
- According to the data, on May latte (dine-in and online) has the highest order number (11 order) followed by tea (dine in) with 8 order in that period
- According to the data, on april coffee (dine-in) is the number one item that get ordered (8 order), followed by tea through online order (8 order), and burger (online) with 7 order during that month--April


