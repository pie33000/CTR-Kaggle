# CTR-Kaggle
In online advertising, click-through rate (CTR) is a very important metric for evaluating ad performance. As a result, click prediction systems are essential and widely used for sponsored search and real-time bidding.

For this competition, we have provided 11 days worth of Avazu data to build and test prediction models. Can you find a strategy that beats standard classification algorithms? The winning models from this competition will be released under an open-source license.

## Data Description

train - Training set. 10 days of click-through data, ordered chronologically. Non-clicks and clicks are subsampled according to different strategies.
test - Test set. 1 day of ads to for testing your model predictions. 
sampleSubmission.csv - Sample submission file in the correct format, corresponds to the All-0.5 Benchmark.
Data fields

id: ad identifier
click: 0/1 for non-click/click
hour: format is YYMMDDHH, so 14091123 means 23:00 on Sept. 11, 2014 UTC.
C1 -- anonymized categorical variable
banner_pos
site_id
site_domain
site_category
app_id
app_domain
app_category
device_id
device_ip
device_model
device_type
device_conn_type
C14-C21 -- anonymized categorical variables

Competition Link : https://www.kaggle.com/c/avazu-ctr-prediction
