
## Project Overview

Exploratory Data Analysis of Customer Behaviour for Accepting Different kinds of Coupons (Restaurents, bars, coffee houses, takeaway etc) while driving under different conditions that could influence the decision or accepting / rejecting.

The goal of this project is to use data analysis technique such as Statistical Summarization, Plotting and Visualization to understand the data.

---

## Link to Jupyter notebook 
https://github.com/ashok0282/eda-customer-coupon-analysis/blob/main/prompt.ipynb

---
## Data Set

The survey data describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

1) “Right away”
2) “Later, before the coupon expires”
3) “No, I do not want the coupon”

The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” 
There are five different types of coupons: 
- Less expensive restaurants (under $20)
- coffee houses
- carryout and takeaway
- bars
- more expensive restaurants ($20–$50).

---

## Summary of Key Findings
Ensure that your findings are clearly stated in a separate section alongside actionable items and recommendations.
Your repository should also include a READMe file containing a brief nontechnical report that highlights the differences between customers who did and did not accept the coupons.


## Overall acceptance rate across all coupons
- Total Observations: 12007
- Acceptance: 6825
- Percentage Acceptance: 56.84%

## Investigating Bar Coupons

### Overall Bar Coupons Acceptance 

- Total Coupons = 1906 
- Accepted = 785 
- Percentage Acceptance = 41.18%
- Acceptance rate for Drivers visited bar 3 or less time in a month is 37.24% is much less compared to drivers visited >3times per month 76.16%
- Acceptance rate of drivers visit bar more than once a month and over age 25 is 70.91% compared to age under 25 is 29.08% percentage 
- Acceptance rate for drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry.
is much higher 65.73% compared to acceptance rate with kid passenger percentage: 2.79%
- Acceptance rate for drivers go to Bar more than once and no kid passenger and were not widowed =70.94%
- Acceptance rate for drivers go to Bar more than once and under age 30 = 71.95%
- Acceptance rate for drivers go to cheap restaurants more than 4 times a month and income is less than 50K = 45.64%

### Hypothesis
- Drivers visiting more than 3times per month are more likely to accept bar coupons.
- Drivers with no kid passenger are more likely to accept.
- Drivers with kid passenger are not likely to accept.
- Drivers of age group over 25 years is more likely to accept bar coupons

---

## Analyzing Coffee House Coupons

### Overall Acceptance rate of Coffee House Coupons
- Total Coffee House Coupon: 3809
- Accepted Coffee House Coupon: 1888
- Percentage of Coffee House Coupons Accepted: 49.56%

### Examine acceptance by age group under 30 vs over 30 years
- Total Coffee House Coupons = 3809
- Accepted Coffee House Coupons = 1888
- Accepted Coffee House Coupons Under age 30 = 943
- Accepted Coffee House Coupons Over age 30 = 945
- Proportion Accepted Coffee House Coupons Under age 30 Percentage = 49.94%
- Proportion Accepted Coffee House Coupons Over age 30 Percentage = 50.05%

### Examining acceptance by group income under 50K vs over 50K
- Accepted Coffee House Coupons income under 50K = 1066
- Accepted Coffee House Coupons income over 50k = 822
- Proportion Accepted Coffee House Coupons Income under 50K Percentage = 56.46%
- Proportion Accepted Coffee House Coupons Income over 50K Percentage = 43.53%


### Hypothesis 
- Acceptance by age group below 30 and over 30 is almost similar
- Acceptance rate is higher for income under 50K compared to over 50K income

- #### Examining Relationship of acceptance by occupation type
  - Highest acceptance by Unemployed, Student , Computer & Mathematical compared to rest of the occupations!

- #### Examining Relationship of acceptance by weather
  - Sunny Weather has higher acceptance!

- #### Examining Relationship of acceptance by gender
  - Pretty even acceptance rate between Male vs Female!

- #### Examining Relationship of acceptance by 'time' of day
  -  Highest acceptance is early morning between 7AM - 10 AM and second highest is 6 PM and lowest is in night 10 PM!
 
## Some Recommendation
### Bar Coupons
- Target Drivers that visit more than 3 times per month to Bar
- Target Drivers with no kid passenger
- Target Drivers with age group over 25

### Coffee Coupons
- Target drivers income less than 50K
- Target drivers who are unemployed, students or working in Computer and Mathematical 
- Target more in sunny weather
- Target during morning 7 AM - 10 AM or evening 6 PM

