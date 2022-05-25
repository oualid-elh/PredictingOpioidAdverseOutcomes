![Step of our calculation](images/boussardlab.png "Boussard Lab")

# Postoperative Pain Management - Medicaid

## Objectives

The purpose of this project is to develop a stratification tool that flags Medicaid members who are at high risk for opioid abuse, dependence and overdose following surgery. The project involves a cohort selection/construction process, feature construction, statistical analysis and machine learning predictive modeling. Here, we provide the code for the statistical analysis and ML modeling. 

## Code usage

1. [Models](./Models/): Contains the Jupyter notebooks for the models trained and evaluated for both the primary outcome and the secondary outcome (which is persistent opioid use). Also contains a notebook for evaluating calibration and discrimination.

2. [Statistical Analysis](./Statistical analysis/): Contains the Jupyter notebooks used for conducting statistical analysis on the cohort. The file `Descriptive_statistics.ipynb` was used to generate the Table 1 statistics (i.e descriptive statistics about demographics stratified by outcome) and to measure the bivariate association between the outcome and the diagnosis variables Diabetes, Depression, Obesity, in absolute value and across years. The file `Statistical_trend_test.ipynb` is used to do a t-test on regression slopes for comparison of the trends of the primary outcome evolution, between 2016 and 2020, for vulnerable populations.



## Other folders

* [Resources](./Resources/): Contains all the external files (non-HMS) used in the code. For example, it contains the CCSR categories for diagnosis and procedures, opioid information files (e.g CDC_opioids.csv), the ICD/CPT codes used for surgery, the ICD codes used for flagging opioid dependence, abuse and overdose.


## Code requirements

![Step of our calculation](images/requirements.png "Requirements")






