# take-home-interview

take home interview for data scientist role. my goal for this repository was primarily to illutrate deep learning modeling skillset; please ignore any glaring neglect to foundataional methodology or domain implications, e.g. residual distribution, contextual interpretation of large rmse, etc.



---



---


## ********************* Research Challenge:
### NYC Property Sales Data prediction

---


In this notebook I perform several analyses on Manhattan property sales data from 2020-2021.

My analyses can be summarised as the following
- 1. Build understanding through data cleaning and exploratory data analysis.
- 2. Conduct hypothesis tests to estimate relationships between key variables
- 3. Fit a wide range of machine learning and deep learning models to predict Manhattan property sales data.
<br><br>

**Motivation:**
Build supervised learning model to predict property sales prices to uncover buy and sell opportunities for undervalued and overvalued properties, respectively. Although we would need real time property listing data to uncover inefficiencies in the Manhattan property market, building a predictive model with high performance would be the first step to detect said inefficiencies. 
<br><br>

**Loss metric:**:
Across predictive modeling tasks I optimize for RMSE. I chose RMSE over MAE because I am assuming we are sensitive to outliers in the target and particularly bad model predictions. On the other hand, results for MAE are more interpretable as they are on the same scale.
<br><br>

**Hypothesis:**
While I define formal null and alternative hypotheses (with OLS regression assumptions about the features and target) for the MLR hypothesis testing, my hypothesis for the predictive modeling is as follows: 

Increasing our feature set size, engineering features with denoising autoencoders, and increasing model complexity will allow use to improve upon baseline model performance (baseline model is OLS with restricted feature set). While this might be trivial, it will be interesting to see which techniques increase model performance and to what extent.

