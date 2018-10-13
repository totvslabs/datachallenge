<b>TOTVS Labs - Data Science Challenge</b>

The purpose of this challenge is to let you demonstrate the way you think and work. The [dataset](https://github.com/totvslabs/datachallenge/raw/master/challenge.zip) we are providing contains the orders made by customers in one of our applications. Here’s the description of each column:

* customer_code: unique id of a customer;
* branch_id: the branch id where this order was made;
* sales_channel: the sales channel this order was made;
* seller_code: seller that made this order;
* register_date: date of the order;
* total_price: total price of the order (sum of all items);
* order_id: id of this order. A order is formed by a set of items;
* item_code: code of the item;
* quantity: quantity of items, given by item_code, were bought;
* item_total_price: total price of items, i.e., quantity* price;
* unit_price: unit price of this item;
* group_code: which group this customer belongs;
* segment_code: segment this client belongs;
* is_churn: True, if we believe the client will not come back. (for a `customer_code` this values is always the same)

There are many possible use cases for this data, e.g., product recommendation, churn analysis, sale forecasting, etc.  Pick one use case and build a model for this case. We want to test your skills in data manipulation, cleaning, and predictive modeling, so, please explain each of your design choices, you can use jupyter notebooks for all your exploration and modeling. (e.g., EDA, preprocessing, model selection, hyperparameters, evaluation criteria, etc. )

You shouldn’t spend more than 5 hours to complete the exercise.

You can find the dataset for this challenge in the following url:
https://github.com/totvslabs/datachallenge/raw/master/challenge.zip

PS: Ideally, we should be able to replicate your analysis from your submitted source-code, so please explicit the versions of the tools and packages you are using.
