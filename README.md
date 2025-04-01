# NY-State-Hospital-Length-of-Stay-Cost-Forecasting

Hospitals often struggle to accurately predict hospitalization costs due to various factors, including demographic, medical, and financial variables. This project aims to identify the key drivers of these costs and develop a predictive model that forecasts expenses based on patient characteristics and length of stay.
Using a dataset of inpatient discharges from the New York State Department of Health (1.6M rows), the analysis explores cost patterns and influential factors. A preprocessing pipeline was built in Python with Pandas and Scikit-Learn to clean and transform the data, incorporating recursive feature selection to refine inputs before training. Machine learning models, including decision trees, random forests, XGBoost, and linear regression, were fine-tuned through Bayesian optimization, grid search, and random search. XGBoost demonstrated the best performance, achieving the lowest RMSE.

# Contributors
Courtney Vincent
Crystal Leatvanich
Sanjal Desai
Rebecca Bubis
