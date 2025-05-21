### Issue / Problem
The New York City Taxi & Limousine Commission (TLC) contracted Automatidata to develop a model for predicting taxi fares. For this initial phase of the project, Automatidata's data team delivered a regression model, addressing the TLC's original request.

### Response
Given the nature and distribution of the available data, the Automatidata team opted for a multiple linear regression (MLR) model to predict taxi fares. This model proved effective in estimating fares before a ride commences.

Performance was strong across both training and test datasets, indicating neither significant bias nor overfitting. Notably, the model exhibited slightly better performance on the held-out test data.

### Impact
Addressing outliers, particularly in `fare_amount` and `duration`, further optimized the model's performance. The resulting linear regression model provides a robust foundation for estimating taxi fares.

![image](https://github.com/user-attachments/assets/ad1fd432-110d-4ef3-b24d-48b4e221d466)


### Model Metrics
- **R² = 0.87** (86.8% of variance described by the model)
- **MAE = 2.1**
- **MSE = 14.36**
- **RMSE = 3.8**

### Key Insights
- Ride duration had the most significant impact on fare amount.
- The model suggests an average increase of $7 per additional minute, but due to multicollinearity, this is not a precise causal relationship.
- Recommend collecting more data, especially for under-represented ride itineraries.

**Potential Use Case:**  
TLC can develop a user-facing app to provide fare estimates before a ride begins.
