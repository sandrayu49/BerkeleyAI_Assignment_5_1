# Berkeley AI Certificate Assignment 5_1
The goal of this assignment is to determine what kind of customer will likely to accept the coupon.

## Data Source
https://github.com/sandrayu49/BerkeleyAI_Assignment_5_1/tree/main/data

## Data Columns
| Column Name | Type |
| --- | --- |
| destination  | object
| passanger | object
| weather | object
| temperature | int64 
| time | object
| coupon | object
| expiration | object
| gender |  object
| age | object
| maritalStatus | object
| has_children | int64 
| education | object
| occupation | object
| income | object
| car | object
| Bar | object
| CoffeeHouse | object
| CarryAway | object
| RestaurantLessThan20 | object
| Restaurant20To50 | object
| toCoupon_GEQ5min | int64 
| toCoupon_GEQ15min | int64 
| toCoupon_GEQ25min | int64 
| direction_same | int64 
| direction_opp | nt64 
| Y  | int64 

## Observations
Based on the data given, roughly 56% of coupons are accepted. The most popular coupons are coffee house, take out place and nearby restaurants. Also drivers are more likely to accept the coupon when the weather is sunny and warm.
Look into the passanger information, turn out that drivers are more likely to accept coupons when they drive alone. Going a little bit deeper into the who other factors that may influence on the coupon acceptance rate, I found the followings:
Here are the characteristic of drivers who are more likely to accept coupon:
* Drivers who are not driving to urgent places
* Drivers without passangers
* Drivers who are under the age of 31
* Drivers who are either single, married or with partners.
* Drivers with income less than 63K

