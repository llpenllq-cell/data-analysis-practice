\# Data Analysis Practice



Practice repository for learning data analysis, statistics, and  maybe a bit of machine learning.

# Advertising Sales Analysis

## Exploratory Data Analysis Summary

### Data Quality

The dataset contains 200 observations and four main variables:

* `TV`
* `radio`
* `newspaper`
* `sales`

No missing values or duplicate rows were found in the dataset.

### Distributions

The `sales` variable has an approximately symmetric distribution.

The `newspaper` variable is positively skewed, with a skewness value of approximately `0.89`.
### Outliers

Using the IQR method, two outliers were detected in the `newspaper` variable.


### TV Advertising and Sales

TV advertising shows the strongest relationship with sales among the three advertising channels.

The correlation between `TV` and `sales` is approximately:

`0.70`

The scatter plot also shows a relatively clear positive linear relationship.

This means that higher TV advertising spending tends to be associated with higher sales.

However, correlation alone does not prove that TV advertising directly causes the increase in sales.

### Radio Advertising and Sales

Radio advertising has a moderate positive relationship with sales.

The correlation between `radio` and `sales` is approximately:

`0.50`

The scatter plot shows more variability than the TV–Sales relationship, meaning that sales are less consistently related to radio advertising spending.

### Newspaper Advertising and Sales

Newspaper advertising shows a weak linear relationship with sales.

The correlation between `newspaper` and `sales` is approximately:

`0.20`

The scatter plot is highly dispersed, suggesting that newspaper advertising alone does not have a strong linear association with sales in this dataset.

This does not necessarily mean that newspaper advertising has no effect on sales; it only means that a strong linear relationship is not visible in this dataset.

## Overall Conclusion

Among the three advertising channels, TV advertising has the strongest observed association with sales.

Radio advertising also shows a positive relationship with sales, although the relationship is weaker and more variable.

Newspaper advertising shows only a weak linear relationship with sales.

The exploratory analysis therefore suggests that TV advertising may be the most useful variable for explaining or predicting sales among the three available advertising channels.

Further statistical analysis and regression modeling would be required to better quantify these relationships and evaluate their predictive value.

