******************************** India vs Australia 2019 ODI series prediction **********************************

Source: ESPN Cricinfo

********************************  Series Winner & Margin Prediction ********************************************
Data that is taken into consideration for Series winner prediction:
1. India Vs Australia matches played in India for the last ten years
2. India's all matches for the past 2 years
3. India's all home matches for past 4 years
4. India vs all opposition teams played at the venues of the upcoming odi series- Hyderabad,ranchi, Delhi,Nagpur & Mohali

Data cleaning & Preparation:
Extracted the year from Start Date as only year is important in our analysis.
Form Indicator variable is created which gives weightage to the recent form the teams.
Removed all the columns which are not required for the problem at hand.
Created the dummy variables for all the categorical variables.


Data modelling:
This is Classification problem. Predicting win/loss
Used Random Forest as it is good in handling categorical variables.


Model Evaluation:
As the data is not that large, total data has been used as training data
Created test cases for prediction and used them as the test data
Ran the model for 10 times and took the avverage all the 10 runs for predicting winner of the series

Results:
India with a win percentage of 76%. So the series would be 4-1 in favor of India

Winner of the series- India(4-1)
win margin: India 4 - Australia 1

**********************************************************************************************************************

******************************* Individual Performances Prediction **************************************************

Data that is taken into consideration for runs,4s,6s & wickets prediction:
1. India's all matches for the past 2 years
2. Australia's all matches for the past 2 years
3. India's home matches for the past 4 years
4. Australis's away performance for the past 4 years
5. India vs all opposition played at the venues of the upcoming odi series- Hyderabad,ranchi, Delhi,Nagpur & Mohali
6. India Vs Australia matches played in India for the last ten years

Data cleaning & Preparation:
Extracted the year from Start Date as only year is important in our analysis.
Removed all the columns which are not required for the problem at hand.
Created the dummy variables for all the categorical variables.

Data modelling:
This is regression problem. Predicting runs, 6s ,4s and wickets
Used Linear Regression we need to predict a continuous output.


Model Evaluation:
As the data is not that large, total data has been used as training data
Created test cases for prediction and used them as the test data

Results:
Virat Kohli - Highest number of runs in the series

Rohit Sharma - Highest number of sixes in the series

Virat Kohli - Highest number of fours in the series

Kuldeep Yadav - Highest number of wickets in the series
