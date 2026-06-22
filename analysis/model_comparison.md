# Model Comparison

## Overview
Three regression models were assessed to identify the key factors associated with monthly sales performance.

---

## Model 1: Marketing Spend Regression

### Dependent Variable
* Monthly Sales

### Independent Variable
* Marketing Spend

### R-Squared
* 0.167

### Significant Variables
* Marketing Spend

### Business Interpretation
Marketing spend shows a positive and statistically significant association with monthly sales. That said, the model accounts for only a modest share of the overall variation in sales.

### Limitations
* Does not factor in customer traffic
* Customer satisfaction is not considered
* Overall explanatory power is limited

---

## Model 2: Footfall Regression

### Dependent Variable
* Monthly Sales

### Independent Variable
* Footfall

### R-Squared
* 0.736

### Significant Variables
* Footfall

### Business Interpretation
Footfall emerges as a strong predictor of sales and captures a large proportion of the variation in monthly sales figures.

### Limitations
* Marketing effects are not included
* Regional differences are not accounted for
* Customer experience factors are excluded

---

## Model 3: Multiple Regression

### Dependent Variable
* Monthly Sales

### Independent Variables
* Marketing Spend
* Footfall
* Inventory Availability
* Customer Rating
* Region_North
* Region_South
* Region_East

### R-Squared
* 0.814

### Significant Variables
* Marketing Spend
* Footfall
* Customer Rating
* Region_East

### Business Interpretation
This model delivers the most comprehensive explanation of monthly sales performance and supports business decision-making across several operational dimensions.

### Limitations
* Certain variables did not reach statistical significance
* Additional business factors outside the dataset may remain uncaptured

---

## Comparison Table

| Model                     | Variables Used                                                                     | R-Squared | Significant Variables                                   | Business Usefulness |
| ------------------------- | ---------------------------------------------------------------------------------- | --------- | ------------------------------------------------------- | ------------------- |
| Marketing Spend Model     | Marketing Spend                                                                    | 0.167     | Marketing Spend                                         | Moderate            |
| Footfall Model            | Footfall                                                                           | 0.736     | Footfall                                                | High                |
| Multiple Regression Model | Marketing Spend, Footfall, Inventory Availability, Customer Rating, Region Dummies | 0.814     | Marketing Spend, Footfall, Customer Rating, Region_East | Very High           |

---

## Final Model Selection
The Multiple Regression Model was chosen as the final model on account of its highest R-squared value and superior explanatory power for monthly sales performance.
