### Project Overview
This phase of the project focuses on uncovering how the payment method influences taxi fare amounts. By analyzing the relationship between `payment_type` and `total_amount`, the goal is to derive actionable insights that can help increase revenue for NYC taxi drivers.

### Problem
Drivers receive inconsistent tip amounts depending on how customers pay.

**Key Question:**
> Do credit card users tend to spend more than cash users?

### Solution
An A/B test was designed and implemented to test this hypothesis:
- **Group A:** Required to pay by credit card.
- **Group B:** Required to pay in cash.

The team then compared the `total_amount` between the two groups using a two-sample t-test.

### Details
**Steps Conducted in the A/B Test:**
- Collected randomized experimental data.
- Performed descriptive statistics to understand fare distributions.
- Conducted hypothesis testing (A/B test) using a two-sample t-test.

**Result:**  
A/B test results show a statistically significant difference in the average total fare between customers who use credit cards and those who use cash. Customers who paid with credit cards had a higher total fare.

### Key Insight
Encouraging customers to pay with credit cards may increase revenue for taxi drivers and the TLC.

### Next Steps
Recommend TLC to promote credit card payments with signs in taxis or driver scripts.

