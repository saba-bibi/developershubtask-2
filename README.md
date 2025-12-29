# developershubtask-2
Data Science &amp; AI/ML Engineering – Advanced Internship Tasks 


✅ Task 1: Term Deposit Subscription Prediction (Bank Marketing)
🎯 Objective

Predict whether a bank customer will subscribe to a term deposit following a marketing campaign.

🛠 Approach

Loaded and explored the UCI Bank Marketing dataset

Encoded categorical features using One-Hot Encoding

Trained Logistic Regression and Random Forest classifiers

Evaluated models using Confusion Matrix, F1-Score, and ROC Curve

Applied SHAP to explain individual customer predictions

📊 Key Results

Random Forest outperformed Logistic Regression in F1-Score

Campaign duration and previous outcomes strongly influenced subscriptions

SHAP explanations provided transparency into customer-level decisions

🔍 Conclusion (Task 1)

The model successfully predicts term deposit subscriptions and highlights key behavioral drivers. Explainable AI (SHAP) enables interpretable, trust-worthy predictions suitable for real marketing decision-making.

✅ Task 2: Customer Segmentation Using Unsupervised Learning
🎯 Objective

Segment customers based on spending behavior to support targeted marketing strategies.

🛠 Approach

Conducted Exploratory Data Analysis (EDA)

Applied K-Means clustering on income and spending score

Determined optimal clusters using the Elbow Method

Visualized clusters using PCA

Proposed marketing strategies for each segment

📊 Key Results

Identified 5 distinct customer segments

Clear behavioral differences observed across clusters

PCA visualization improved interpretability

🔍 Conclusion (Task 2)

Customer segmentation revealed actionable behavioral groups that enable personalized marketing. These insights can significantly improve customer engagement and revenue optimization.

✅ Task 3: Energy Consumption Time Series Forecasting
🎯 Objective

Forecast short-term household energy consumption using historical time-series data.

🛠 Approach

Parsed and resampled time-series data

Engineered time-based features

Trained and compared ARIMA, Prophet, and XGBoost models

Evaluated performance using MAE and RMSE

Visualized actual vs forecasted consumption

📊 Key Results

XGBoost captured nonlinear patterns most effectively

Prophet handled seasonality well

ARIMA provided baseline temporal modeling

🔍 Conclusion (Task 3)

Advanced forecasting models accurately predicted energy usage trends. Machine-learning-based approaches outperformed traditional time-series models for complex consumption patterns.

✅ Task 4: Loan Default Risk with Business Cost Optimization
🎯 Objective

Predict loan default risk and optimize decision thresholds using business cost analysis.

🛠 Approach

Trained an XGBoost classification model

Defined asymmetric costs for false positives and false negatives

Optimized probability threshold to minimize total financial loss

Visualized cost-threshold trade-offs

📊 Key Results

Identified an optimal decision threshold minimizing business loss

Demonstrated how accuracy alone is insufficient for business decisions

🔍 Conclusion (Task 4)

Cost-sensitive modeling aligns machine-learning predictions with real business objectives. Threshold optimization significantly reduces financial risk compared to default classification rules.
