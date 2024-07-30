## -walmart_sales_forecasting
This project involves predicting weekly sales for Walmart stores across different departments using historical sales data.

## Executive summary

Project involves the use of Linear Regression, Support Vector Regression, Decision Tree, Random Forest Regression and Xgboost to measure the possible best outcome. Validated the models using cross-validation and performance metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R<sup>2</sup> value to ensure robustness. The results demonstrated that ensemble learning method is effective by using RandomForest model acquiring an adjusted R<sup>2</sup> value of 0.97, significantly outperforming other used regression models like linear regression and support vector machine. Tools such as Pandas, NumPy, Seaborn and Scikit-learn were utilized for data preprocessing, visualization and model building. The dataset consisted of 8190 rows and 12 columns, with a 80/20 split for training and testing.


## Technical overview

Below I outline briefly the main steps in the workflow that i have done with the  Jupyter notebook.

| Task | Summary |
| --- | --- |
| Explore and clean data | Exploring data, their rows and features also impute missing values. |
| Feature engineering | Converting character type data into integer type using suitable methods. |
| Select algorithm | Compare a number of algorithms using cross validation to identify the most promising performers for this data/feature set. |
| Establish model performance | Use a 20% hold-out test set to compare predicted and observed yields. |



## Future work

for future work there is still many things we can work on, for now these issues could be addressed by:

* getting more data,
* more different features that can play a vital role in this perspect,
* fine tuning the model using various suitable techniques,or
* using ensemble techniques by combining the results of different models.
