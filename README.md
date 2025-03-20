CloverShield Insurance Call Prediction

This project aims to develop a predictive model for CloverShield Insurance Company to forecast the number of calls a policyholder is likely to make. The goal is to optimize resource allocation and enhance cost-efficiency in call center operations.

Business Problem: CloverShield Insurance is looking to reduce call center costs by leveraging machine learning to predict policyholder call counts. This model will help optimize staffing and improve customer service by anticipating call volumes more accurately.

Modeling Approach: The project workflow included data preprocessing, modeling, and evaluation. Data preprocessing involved one-hot encoding of categorical variables and capping outliers at the 5th and 95th percentiles. For modeling, the benchmark model was a LightGBM regressor without tuning or feature manipulation. Hyperparameter tuning was performed using Grid Search to enhance performance. The model's predictions were submitted for both training and test datasets, and a presentation summarizing the analysis and findings was prepared for the business partners.

Evaluation Metric: The model is evaluated with the relative Gini index

Disclaimer: CloverShield Insurance Company and the dataset are fictitious, created solely for the purpose of this competition.
