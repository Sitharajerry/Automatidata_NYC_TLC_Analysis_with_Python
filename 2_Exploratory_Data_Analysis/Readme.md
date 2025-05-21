### Project Overview
In preparation for building a predictive regression model, the Automatidata team conducted an exploratory data analysis (EDA) on the TLC dataset to better understand the underlying structure and identify data issues that could impact modeling accuracy.

### Key Insights
- **Problem Identified:** Instances of trips with a `total_amount` recorded but a `trip_distance` of 0 were flagged as outliers or potential data entry issues.
- **Proposed Solution:** Recommend removing all records where `trip_distance = 0` to improve model reliability.

### Keys to Success
- Handle other anomalies such as low distance with disproportionately high fares.
- Ensure with New York City TLC that the sample provided is an accurate reflection of their data as a whole.

### Visualization
As a result of the conducted exploratory data analysis, the Automatidata data team considered `trip_distance` and `total_amount` as key variables to depict a taxi cab ride. The provided scatter plot shows the relationship between the two variables. This scatter plot was created in Tableau to enhance the provided visualization.

![image](https://github.com/user-attachments/assets/5c90f243-ab69-4c00-9456-ad5d9d8f0e32)


### Next Steps
- Determine any unusual data points that could pose a problem for future analysis in predicting trip fares (e.g., locations that have longer durations).
- Determine which variables most significantly affect fare predictions.
- Filter down to consider the most relevant variables for running regression, statistical analysis, and parameter tuning.
