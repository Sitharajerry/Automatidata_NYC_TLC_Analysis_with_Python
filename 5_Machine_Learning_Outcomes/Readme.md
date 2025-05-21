### Overview
 Develop a machine learning model that predicts whether a taxi rider is likely to leave a generous tip.

### Problem
The original goal of predicting non-tippers was reconsidered due to ethical concerns.  
The focus shifted to identifying **generous tippers** (those who tip ≥ 20%).

### Solution
The team built and compared two models—**Random Forest** and **XGBoost**.  
Both performed well, with **Random Forest** slightly outperforming XGBoost.

**F1 Score for Random Forest:** 0.7235

![image](https://github.com/user-attachments/assets/aa55b9b8-d0bc-451c-9d93-a2d48081ae7f)


### Details

**Behind the Data:**
- Assumed features like trip itinerary, fare, duration, distance, and time of day influence tipping behavior.
- VendorID also emerged as a top predictor, possibly reflecting service or operational differences.

### Results Summary
The developed algorithm effectively predicts riders who are likely to be generous tippers, achieving strong precision, recall, F1, and accuracy scores.

### Next Steps
- Consult NYC TLC to share model results and discuss deployment as a tipping indicator.
- Additional data collection needed for further improvements.

### Future Model Suggestions
- Gather more granular data (e.g., past tipping behavior, demographics, ratings).
- Use **K-means clustering** to segment passengers and uncover patterns to improve predictions.

