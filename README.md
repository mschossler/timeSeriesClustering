# Time Series Clustering
In this project, we identify general attributes of businesses’ payment activity based on their transaction history. The results in the report could be used to help Co. better understand customer behavior, thus guiding the decision-making regarding personalized customer experiences. We first analyze the payment activity history of merchants processing with Co. between January 1st, 2033, and December, 31st, 2034. Then, we classify Co.’s customers based on their data and generate attributes for each of them, including predicting near-future transaction activity behaviors.

We first preprocess the data and create a time series for the transactions of each customer, then we optimally split merchants (based on their time series) into 5 classes employing the K-means clustering algorithm. Each class has attributes that help us understand the kind of businesses processing with Co. For example, we can point out customers that are more likely to do transactions frequently and customers that are more likely to stop using Co. in the months following 2034. This was found by comparing their attributes with the attributes of other classes of businesses in the dataset.

The Jupyter notebook contains the algorithms, code, and raw results. The report explains the methodology used and processed results.


Data file ('transaction_history.csv'): https://www.dropbox.com/s/xfbfhyaf3h0us84/transaction_history.csv?dl=0
