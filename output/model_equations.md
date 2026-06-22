# Model Equations

---

## Simple Regression Model 1

### Marketing Spend Model

Monthly Sales = 560777.35 + (2.13 × Marketing Spend)

### Interpretation
For every additional unit of marketing spend, monthly sales are expected to increase by approximately 2.13 units.

R-Squared = 0.167

---

## Simple Regression Model 2

### Footfall Model

Monthly Sales = 446410.58 + (35.68 × Footfall)

### Interpretation
Each additional customer visit is associated with roughly 35.68 additional units in monthly sales.

R-Squared = 0.736

---

## Multiple Regression Model

Monthly Sales =
98015.51
+ (1.20 × Marketing Spend)
+ (33.98 × Footfall)
+ (2886.73 × Inventory Availability %)
+ (11024.99 × Customer Rating)
− (8375.71 × Region_North)
+ (4929.59 × Region_South)
− (17042.83 × Region_East)

---

### Dummy Variable Approach

**Categorical Variable:**

* Region

**Reference Category:**

* West

**Dummy Variables:**

* Region_North
* Region_South
* Region_East

When all dummy variables are set to zero, the record is treated as belonging to the West region.
This approach prevents the dummy variable trap and eliminates the risk of perfect multicollinearity.

---

## Final Model Selected

### Multiple Regression Model

**Reasons for selection:**

* Achieved the highest R-squared value (0.814)
* Provides the strongest explanatory power among all models
* Includes multiple statistically significant predictors
* Offers clearer and more actionable business interpretability
* Best suited for supporting business decision-making

The Multiple Regression Model was chosen as the final model.
