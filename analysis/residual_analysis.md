# Residual Analysis

## Objective
Residual analysis was conducted using the final multiple regression model.

Residual = Actual Sales − Predicted Sales

Positive residuals indicate that actual sales exceeded what the model predicted.
Negative residuals indicate that actual sales fell short of model predictions.

---

## Largest Positive Residuals

| Actual Sales | Predicted Sales | Residual  |
| ------------ | --------------- | --------- |
| 713611.16    | 585781.30       | 127829.90 |
| 625514.04    | 522797.21       | 102716.80 |
| 787715.51    | 687127.02       | 100588.50 |
| 813316.71    | 718839.53       | 94477.18  |
| 799046.94    | 706026.96       | 93019.98  |

### Interpretation
These stores delivered sales results well above what the model anticipated.

Possible explanations include:

* Strong demand driven by local market conditions
* Effective store-level management
* Successful execution of local promotions
* High levels of customer loyalty
* Market dynamics not captured within the dataset

The model under-estimated performance for these stores.

---

## Largest Negative Residuals

| Actual Sales | Predicted Sales | Residual   |
| ------------ | --------------- | ---------- |
| 685379.08    | 841678.34       | -156299.00 |
| 595467.60    | 729696.76       | -134229.00 |
| 627171.90    | 757388.58       | -130217.00 |
| 641865.03    | 762488.83       | -120624.00 |
| 538376.00    | 648422.32       | -110046.00 |

### Interpretation
These stores recorded lower sales than the model projected.

Possible explanations include:

* Pressure from local competitors
* Operational difficulties at store level
* Disruptions within the local market
* Underperforming promotional activity
* External factors outside the scope of the model

The model over-estimated performance for these stores.

---

## Business Conclusion
The model attained an R-squared value of 0.814 and accounts for a substantial share of the variation in sales.

However, the existence of both positive and negative residuals points to additional business factors that influence store-level sales performance beyond what the model captures.

The model is well-suited for supporting business decisions but should not be treated as a flawless predictor of individual store outcomes.
