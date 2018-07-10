<b>TOTVS Labs - Data Science Challenge</b>

The purpose of this challenge is to let you demonstrate the way you think and work. You shouldn’t spend more than 8 hours to complete the exercise.

The [dataset](https://github.com/TOTVS/datachallenge/blob/master/challenge.zip) we are providing contains the orders made by customers in one of our applications. Here’s the description of each column:

* customer_code: unique id of a customer;
* branch_id: the branch id where this order was made;
* sales_channel: the sales channel this order was made;
* seller_code: seller that made this order;
* register_date: date of the order;
* total_price: total price of the order (sum of all items);
* order_id: id of this order;
* quantity: quantity of items, given by item_code, were bought;
* item_total_price: total price of items, i.e., quantity* price;
* unit_price: unit price of this item;
* group_code: which group this customer belongs;
* segment_code: segment this client belongs;
* is_churn: if this client is set as a churn.

<b>Question 1 (10 Points)</b>
<br>List as many use cases for the dataset as possible.

<b>Question 2 (10 Points)</b>
<br>Pick one of the use cases you listed in question 1 and describe how building a statistical model based on the dataset could best be used to improve the business this data comes from.

<b>Question 3 (20 Points)</b>
<br>Implement the model you described in question 2, preferably in Python. The code has to retrieve the data, train and test a statistical model, and report relevant performance criteria. 
Ideally, we should be able to replicate your analysis from your submitted source-code, so please explicit the versions of the tools and packages you are using.

<b>Question 4 (60 Points)</b>
<br>A. Explain each and every of your design choices, you can use jupyter notebooks. (e.g., preprocessing, model selection, hyper parameters, evaluation criteria). Compare and contrast your choices with alternative methodologies. 
<br>B. Describe how you would improve the model in Question 3 if you had more time.

You can find the dataset for this challenge in the following url:
https://github.com/TOTVS/datachallenge/raw/master/challenge.zip
