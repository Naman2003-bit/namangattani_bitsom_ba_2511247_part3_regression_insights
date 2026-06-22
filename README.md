# Regression-Based Business Insights and Model Interpretation

## Business Problem Summary
The purpose of this project was to uncover the factors associated with monthly sales performance across retail stores and translate those findings into actionable business recommendations using regression analysis.

Leadership sought to understand how operational, marketing, customer experience, and regional factors shape store-level sales outcomes.

---

## Dataset Description

**Dataset Used:**
business_regression_data.xlsx

**Total Records:**

* 320 store-month observations

**Variables Included:**

* Store ID
* Month
* Region
* Store Type
* Marketing Spend
* Footfall
* Average Discount Percentage
* Staff Count
* Inventory Availability Percentage
* Competitor Distance
* Holiday Flag
* Customer Rating
* Monthly Sales
* Monthly Profit

---

## Dependent Variable

* Monthly Sales

---

## Independent Variables

### Numerical Variables

* Marketing Spend
* Footfall
* Average Discount Percentage
* Staff Count
* Inventory Availability Percentage
* Competitor Distance
* Customer Rating

### Categorical Variables

* Region
* Store Type

---

## Regression Approach
Three regression models were built and compared:

1. Marketing Spend Regression
2. Footfall Regression
3. Multiple Regression

The aim was to compare the explanatory power of each model and pinpoint the variables most strongly associated with monthly sales.

---

## Dummy Variable Approach

**Categorical Variable Used:**

* Region

**Reference Category:**

* West

**Dummy Variables Created:**

* Region_North
* Region_South
* Region_East

West was omitted and used as the reference category to avoid the dummy variable trap.

---

## Model Comparison Summary

| Model                     | R-Squared |
| ------------------------- | --------- |
| Marketing Spend Model     | 0.167     |
| Footfall Model            | 0.736     |
| Multiple Regression Model | 0.814     |

The Multiple Regression Model achieved the highest level of explanatory power among all three models.

---

## Final Model Selected

**Multiple Regression Model**

**Reasons for selection:**

* Highest R-squared value across all models
* Multiple statistically significant predictors
* Strong and clear business interpretability
* Superior capability to support business decision-making

---

## Business Recommendation
Leadership should direct attention toward the following areas:

* Growing customer footfall at store level
* Optimising marketing spend across channels
* Raising customer satisfaction and experience quality
* Examining and addressing performance gaps in the East region

These variables showed the strongest associations with monthly sales performance in the final model.

---

## Assumptions and Limitations

### Assumptions

* Linear relationships are assumed to exist between the variables.
* Observations are treated as independent of one another.
* Historical data is considered representative of future performance trends.

### Limitations

* Regression identifies associations between variables, not causal relationships.
* Additional factors outside the dataset may also influence sales outcomes.
* Market conditions can evolve, which may affect the reliability of historical relationships.

---

## Screenshots Included

* simple_regression_output.png
* multiple_regression_output.png
* residuals_preview.png
* model_comparison_preview.png

---

## Repository Contents

### Analysis

* regression_workbook.xlsx
* model_comparison.md
* residual_analysis.md

### Outputs

* regression_summary.xlsx
* model_equations.md
* final_recommendation.md

### Screenshots

* simple_regression_output.png
* multiple_regression_output.png
* residuals_preview.png
* model_comparison_preview.png

---

This project illustrates how regression analysis can be applied to drive data-informed business decisions and identify the key factors associated with retail sales performance.
