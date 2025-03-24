# fraudForecasting
A ML classification + forecasting project developed using XG boost in R

Dataset: Kaggle

<img width="753" alt="Screenshot 2025-03-24 at 2 01 22 PM" src="https://github.com/user-attachments/assets/1f36ef6b-0e7f-4a30-bbe5-307659056dfb" />
Fraud Risk Forecasting Model

In this project, we successfully built a fraud risk forecasting model using XGBoost with lag-based features. Our approach included:
	1.	Data Preparation & Feature Engineering:
	•	We aggregated fraud count data on a weekly basis.
	•	Created lag features (lag1, lag2) to capture temporal dependencies.
	•	Included key predictors (Risk_Score, Failed_Transactions_Count_7d) identified from the classification model.
	2.	Model Training & Evaluation:
	•	Trained an XGBoost model for regression using past fraud counts and risk-related features.
	•	Validated on test data, achieving a strong alignment between actual and predicted values.
	3.	Future Fraud Prediction:
	•	Extended the model to predict fraud risk for the next 8 weeks using an iterative approach.
	•	The resulting forecast exhibits reasonable fluctuations, suggesting it has learned seasonality/trends.
 <img width="744" alt="Screenshot 2025-03-24 at 2 29 28 PM" src="https://github.com/user-attachments/assets/8c758e80-95c2-4b17-af49-e08847368913" />
 <img width="716" alt="Screenshot 2025-03-22 at 11 49 59 AM" src="https://github.com/user-attachments/assets/76b050c8-578c-4c5d-b1d7-9335c5296dc2" />
<img width="737" alt="Screenshot 2025-03-22 at 11 55 32 AM" src="https://github.com/user-attachments/assets/68f35a35-1c68-4277-ad20-25aa90cfb762" />
<img width="712" alt="Screenshot 2025-03-23 at 10 11 35 AM" src="https://github.com/user-attachments/assets/e5fd2d05-cacd-40f7-9394-d0a00b713b37" />

 

