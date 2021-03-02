# GEICO Class Imbalance Project
 
# Business Problem:
GEICO provides several ways for its policyholders to make payments. While GEICO's service counselors can take payments over the phone, it is more cost-efficient for customers to make payments through their self-service channels such as online or through the automated phone system. Thus, they would like to use a predictive model to select people to receive a pre-emptive e-mail message designed to encourage them to pay online.

# Task at hand:

We have been tasked with identifying which customers are likely to make a service payment call in the next 5 days. The Datasets folder contains data on customers who have had a bill due in the next 5 days and whether they made a service payment call. 

# Predictive Modeling:
 
We will construct a model that predicts the likelihood that each policyholder will make a service payment call (CALL_FLAG=1). 

# Data Dictionary:
Var Name      | Description
------------- | -------------
DATE_FOR      | Date of Record Processing
Content Cell  | Content Cell
RTD_ST_CD     | Rated State of Policy
CustomerSegment  | Segment the Customer falls into
Tenure  | Years of Tenure with Company
Age  | Age of Policyholder
MART_STATUS  | Marital Status of Policyholder
GENDER  | Gender Of Primary Insured
CHANNEL1_6M  | # payments made through Channel 1 in last 6 months
CHANNEL2_6M  |  # payments made through Channel 2 in last 6 months
CHANNEL3_6M  |  # payments made through Channel 3 in last 6 months
CHANNEL4_6M  |  # payments made through Channel 4 in last 6 months
CHANNEL5_6M  |  # payments made through Channel 5 in last 6 months
METHOD1_6M  |  # of payment made with method 1 (irrespective of channel)
RECENT_PAYMENT  | Payment made in last 15 days (1/0)
PAYMENTS_6M  |  # of total payments in last 6 months
CHANNEL1_3M  |  # payments made through Channel 1 in last 3 months
CHANNEL2_3M  |  # payments made through Channel 2 in last 3 months
CHANNEL3_3M  | # payments made through Channel 3 in last 3 months
CHANNEL4_3M  |  # payments made through Channel 4 in last 3 months
CHANNEL5_3M  |  # payments made through Channel 5 in last 3 months
METHOD1_3M  |  # of payment made with method 1 (irrespective of channel)
PAYMENTS_3M  |  # of total payments in last 3 months
NOT_DI_3M  |  Had this customer been enrolled in automated payments in the last 3 months? 1/0
NOT_DI_6M  |  Had this customer been enrolled in automated payments in the last 6 months? 1/0
EVENT1_30_FLAG  |  Has this customer been sent a cancellation notice in the last 30 days? 1/0
EVENT2_90_SUM  |  How many cancellation notices have been sent in the last 90 days?
LOGINS  |  How many times has this policy logged into self-service online in the last 30 days?
POLICYPURCHASECHANNEL  |  How was this policy purchased? 1/0
------------- | -------------
Call_Flag  |  Was there a service payment 1/0? TARGET VARIABLE
 
 
