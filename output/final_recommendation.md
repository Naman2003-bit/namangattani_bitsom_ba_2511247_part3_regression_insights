# Final Business Recommendation

## Executive Summary
Regression analysis was carried out to identify the factors associated with monthly sales performance across retail stores.

Three models were evaluated:

1. Marketing Spend Regression
2. Footfall Regression
3. Multiple Regression

The Multiple Regression Model delivered the highest explanatory power with an R-squared value of 0.814 and was selected as the final model.

---

## Key Findings

### 1. Footfall is the Strongest Driver of Sales
Footfall demonstrated the most significant relationship with monthly sales.

**Coefficient:**

* 33.98

**Interpretation:**
Greater customer traffic is linked to higher sales performance.

**Business Action:**

* Drive store traffic through targeted promotions
* Strengthen customer acquisition campaigns
* Expand and improve loyalty programs

---

### 2. Marketing Spend Positively Influences Sales
Marketing spend was found to be statistically significant.

**Coefficient:**

* 1.20

**Interpretation:**
Greater investment in marketing is associated with an increase in sales.

**Business Action:**

* Continue allocating budget to high-performing marketing channels
* Monitor and evaluate marketing ROI on a regular basis

---

### 3. Customer Rating Matters
Customer rating showed a positive association with sales outcomes.

**Coefficient:**

* 11024.99

**Interpretation:**
Stores with higher customer satisfaction levels tend to record stronger sales figures.

**Business Action:**

* Prioritize improvements to the overall customer experience
* Raise service quality standards
* Invest in ongoing staff training and development

---

### 4. East Region Underperforms
Region_East was statistically significant and carried a negative coefficient.

**Coefficient:**

* -17042.83

**Interpretation:**
Stores in the East region tend to produce lower sales relative to the reference region.

**Business Action:**

* Examine local market conditions in the East region
* Review pricing strategies and promotional effectiveness
* Assess the competitive landscape in the region

---

## Variables That Should Not Be Over-Interpreted
The following variables did not reach statistical significance:

* Inventory Availability
* Region_North
* Region_South

These variables should be treated with caution, as the observed relationships may be a product of random variation rather than genuine effects.

---

## Risks and Limitations

* Regression reveals associations between variables, not causal relationships.
* Certain business drivers that influence sales may not be present in the dataset.
* Historical patterns and relationships may shift over time.
* Store-level operational factors were not captured in the analysis.

Residual analysis further indicated that a number of stores performed considerably above or below what the model projected.

---

## Why Regression Does Not Prove Causation
Regression analysis identifies relationships between variables but does not establish that one variable directly causes another.

For example:
Higher footfall is associated with stronger sales, but both may be driven by underlying factors such as promotional activity, store location quality, or prevailing local demand conditions.

Regression results should therefore be treated as evidence to inform decision-making rather than proof of cause-and-effect relationships.

---

## Final Recommendation
Leadership should focus on the following priorities:

1. Increasing customer footfall across stores
2. Optimizing marketing spend allocation
3. Improving customer satisfaction and experience
4. Investigating and addressing East region underperformance

The Multiple Regression Model should be adopted as the primary decision-support tool, given that it offers the highest explanatory power and the most actionable business insights among all models evaluated.
