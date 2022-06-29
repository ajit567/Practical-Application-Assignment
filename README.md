# Practical-Application-Assignment

This is a summary of analysis done to determine whether a customer will accept a coupon or not based on certain passenger attributes.

# Overview:
In this practical application assignment, the question that was asked was: “Will a customer accept the coupon?” 
The goal of this project is to use what I knew about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not

# Data:
This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

# Findings:
Analysis was done to highlight the differences between customers who did and did not accept the coupons. <br />
This was done by looking two coupon types:<br />
## a) Bar coupons
Overall, the mean acceptance for coupons were 57% however the mean for bar coupon were 41%.  This shows some other coupon types had higher acceptance
based on analysis bar coupons with following passenger attributes higher acceptance:
---Visited bar more than 3 times a month<br />
---Are above 25 and have more than one bar visit per month<br />
---have more than one Bar per month, having no Kids and not have Farming Fishing & Forestry as occupation<br />
---did not have passengers that were not a kid and were not widowed<br />
---These findings were deduced from the visualizations and descriptive statistics in the notebook
## b) Carry and Take away
Further Analysis was carried out for Carry and Take away coupon. The details for these are as given below<br />
Overall the mean acceptance for coupons were 57%, the mean for Carry out & Take away were 73%<br />
Carry and take away coupons with following attributes had higher acceptance:<br />
---Passenger who did not have work as a destination<br />
---were with friend(s) and Partner as passengar<br />
---Weather is sunny<br />
---Temperature is 30<br />
---Time is 2PM<br />
---Expiration is 1d<br />
---Age is 50Plus<br />
---Marital Status is widowed<br />
---Has some high school degree<br />
---Direction_opp is 1<br />
Occupation wise passengers with following occupation will have higher acceptance rate<br />
---Building & Grounds Cleaning & Maintenance<br />
---Protective Service¶<br />
---Construction & Extraction<br />
---Healthcare Practitioners & Technical<br />
---Healthcare Support<br />
---These findings were deduced from the visualizations and descriptive statistics in the notebook
# Next Steps and recommendation:
Analysis such as above needs to be done on other coupon types as to understand the passenger attributes that accept coupons.  Finally a regression analysis(logistics with P values) needs to ne done to evaluate which varibale has a statistically signifincant impact on coupon acceptance to get the complete picture.
