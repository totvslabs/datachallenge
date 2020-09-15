<b>TOTVS Labs - Data Science Challenge</b>

The purpose of this challenge is to let you demonstrate the way you think and work. The [dataset](https://github.com/totvslabs/datachallenge/raw/master/challenge.zip) we are providing has two tables: 

1. `orders.json` contains the orders made by customers in one of our applications between '2008-01-04' and '2018-07-08'. Here's the description of each column:
    * `customer_code`: unique id of a customer;
    * `branch_id`: the branch id where this order was made;
    * `sales_channel`: the sales channel this order was made;
    * `seller_code`: seller that made this order;
    * `register_date`: date of the order;
    * `total_price`: total price of the order (sum of price of all items);
    * `order_id`: id of this order. A order is formed by a set of items;
    * `item_code`: code of the item;
    * `quantity`: quantity of items (of item_code) bought;
    * `item_total_price`: total price of items (of item_code), i.e., quantity* unit_price;
    * `unit_price`: unit price of this item (of item_code);
    * `group_code`: group this customer belongs;
    * `segment_code`: segment this customer belongs;

2. `is_churn.json` contains the 2 columns
    * `customer_code`: unique id of a customer;
    * `is_churn`: If the client is a churn on 2018-08-01.  
    
Notes:
- The primary key of the orders.json table is: `order_id` + `item_code`.
- `is_churn` was recorded for all customers on 2018-08-01 irrespective of when they actually churned prior to 2018-08-01. For example, let us say, Customer1 churns in 2010 and Customer2 churns in 2016. For both customers, the record of `is_churn=1(yes)` was made on 2018-08-01. 

There are many possible use cases for this dataset. For example, product recommendation, churn analysis, sale forecasting, etc.  Pick one use case and build a model for this case. We want to test your skills in data manipulation, cleaning, and predictive modeling. So, please explain all your design and analysis choices. You can use jupyter notebooks for all your exploration and modeling (e.g., EDA, preprocessing, model selection, hyperparameters, evaluation criteria, etc.). You shouldn't spend more than 5 hours to complete the exercise.

You can find the dataset for this challenge in the following url:
https://github.com/totvslabs/datachallenge/raw/master/challenge.zip

PS: Ideally, we should be able to replicate your analysis from your submitted source-code, so please explicit the versions of the tools and packages you are using.

 Please share the zip file of your solution privately OR share your private git repo containing the solution with us.
