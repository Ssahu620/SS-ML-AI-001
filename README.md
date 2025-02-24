# SS-ML-AI-001
Assignment 5.1
Data clean up:
Columns that have missing values are:
1)	“car”
2)	“Bar”
3)	“CoffeeHouse”
4)	“CarryAway”
5)	“RestaurantLessThan20”
6)	“Restaurant20To50”
My steps for data cleanup are as follows:
1)	Drop column “car” – Majority of data under “car” column is null and “car” will not have a major impact on the acceptance rate so column “car” should be dropped.

2)	Replace missing values in “Bar”, “RestaurantLessThan20”, and “Restaurant20To50” to the most frequent values in their value set because mot frequent value is way more than any other value and relacing missing value with this value will have least impact in statistical analysis.


3)	Replace missing values in “CoffeeHouse” and “CarryAway” to a new category “Missing Val”. Reason for it is because frequency of values in these categories are quite similar and small addition to any of these values will skew the results.

My conclusions of people who are going to accept the coupons are as follows:

1)	In total 56.84% of drivers accepted the coupon. 
2)	Among people who visit the bar 41% accepted the coupon.
3)	Within “Bar” group, 33.42% acceptance rate is for drivers who visited the bar 3 times or fewer.
4)	Approximately 50% of Bar coupons were used by drivers who go to bars more than once a month had passengers that were not kids and drivers were not widowed.
5)	Among “CoffeeHouse” coupons majority of drivers who accepted were women.
6)	Among “CoffeeHouse” coupons majority of drivers used coupons at 10:00 AM when they were not going at any particular place.

