# nyc-property-price-deep-learning-demo

---

take home interview for data scientist role. this repository is primarily to demonstrate deep learning modeling skillset, e.g. neural network architecture search (NAS) for nyc property price prediction (supervised) and denoising autoencoder nas (latent feature engineering). custom data cleaning modules, exploratory data analysis, and multiple linear regression parameter hypothesis testing also included.

---

---


## Research Challenge:
### NYC property price prediction

---


In this notebook I perform several analyses on Manhattan property sales data from 2020-2021.

***My analyses can be summarised as the following:***
- Build understanding through data cleaning and exploratory data analysis.
- Conduct hypothesis tests to estimate relationships between key variables
- Fit a wide range of machine learning and deep learning models (NAS for supervised nn and denoising autoencoder) to predict Manhattan property sales data.
<br><br>

**Motivation:**
Build supervised learning model to predict property sales prices to uncover undervalued and overvalued properties. 
<br>

**Loss metric:**:
Across predictive modeling tasks we optimize for RMSE. We choose RMSE over MAE because we am assuming we are disproportionally sensitive to bad model predictions. 
<br>

**Hypothesis:**
While I define formal null and alternative hypotheses (with OLS regression assumptions about the features and target) for the MLR hypothesis testing, my hypothesis for predictive modeling is the following: 

> Increasing our feature set size, engineering features with denoising autoencoders, and increasing model complexity will allow use to improve upon baseline model performance (baseline model is OLS with restricted feature set). While this might be trivial, it will be interesting to see which techniques increase model performance and to what extent.

---
---

### ***Table of contents:***
---
#### 1. Data preparation and exploratory data analysis 
> a. Missing data and outlier removal
<br>b. Encoding and scaling
<br>c. Exploratory data analysis

#### 2. Hypothesis testing with Multiple Linear Regression
>a. Null Hypothesis testing for f-test and t-test
<br>b. Hypothesis testing and regression output

#### 3. Predictive modeling
>a. establish baseline model
<br>b. comparision of supervised learning methods on small feature set
<br>c. clean features for medium feature set
<br>d. comparision of supervised machine learning models on medium feature set
<br>e. neural network architecture search (optimize network topology, e.g. layers, nodes, dropout, etc.)
<br>e. denoising autoencoder neural architecture search
<br>f. denoising autoencoder latent feature extraction
<br>g. neural network prediction on denoised feature set

#### 4. Takeaways and next steps
>a. Data cleaning
<br>b. EDA
<br>c. Hypothesis testing
<br>d. Predictive modeling
<br>e. Time spent

---
