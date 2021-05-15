# Predicting-Changes-in-Annual-Reports-using-R

This project is hosted by the Kaggle private competition and the dataset will not be provided to the public.
The project seeks to create a model that will be able to identify signals that predict what percentage of change year-on-year there is in a company’s annual report and we had to gather our features first with huge autonomy and flexibility in terms of what to include. We ultimately settled upon 3 sources.
•	Compustat (financial ratios)
•	Fog (readability)
•	Sentiment analysis

Key findings from EDA
1)	Active / Dormant Companies - inactive companies have slightly higher median and quartiles of changes in annual reports.
2)	Market Valuation - companies with higher market capitalisations tend to have more boilerplate disclosures.
3)	Auditors and Audit Opinion - companies with Big Four and Mid Tier auditors have a lower median and quartiles of changes in annual reports.

Machine Learning Models
1) Linear Regression
2) Lasso Regression
3) XGBoost

Evaluation of models
Our XGBoost is the best performing model with a Kaggle RMSE Score of 0.05027 (5th out of 19 teams) 

Further consideration
More external data sources such as external GDP, share price movements or industry specific indices can be included to train the model to provide a better RMSE score.
