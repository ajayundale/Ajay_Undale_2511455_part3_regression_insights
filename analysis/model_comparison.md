# Model Comparison

## Objective

The objective of this analysis was to determine which business factors are most strongly associated with monthly sales and identify the regression model that provides the best explanatory power for decision-making.

---

## Models Evaluated

### Model 1 – Simple Linear Regression (Marketing Spend)

* **Dependent Variable:** Monthly Sales
* **Independent Variable:** Marketing Spend

**Results**

* R-squared: **0.16724469112487**
* Coefficient: **2.129575328**
* P-value: **2.48006151013601E-14**

**Business Interpretation**

The model measures the relationship between marketing expenditure and monthly sales. A positive and statistically significant coefficient indicates that higher marketing investment is associated with higher monthly sales.

---

### Model 2 – Simple Linear Regression (Footfall)

* **Dependent Variable:** Monthly Sales
* **Independent Variable:** Footfall

**Results**

* R-squared: **0.73628534**
* Coefficient: **35.67803107**
* P-value: **4.75036150900547E-94**

**Business Interpretation**

The model evaluates whether stores receiving higher customer traffic generate greater monthly sales.

---

### Model 3 – Multiple Linear Regression

**Dependent Variable**

* Monthly Sales

**Independent Variables**

* Dummy_Mall
* Dummy_Residential
* marketing_spend
* footfall
* avg_discount_pct
* staff_count
* inventory_availability_pct
* competitor_distance_km
* holiday_flag
* customer_rating
* Marketing Spend

**Results**

* R-squared: **0.843381815475473**
* Adjusted R-squared: **0.838313265814485**
* F-statistic Significance: **5.15982432073494E-118**

---

## Model Comparison Summary

| Model               | Variables Used                                              | R²  | Significant Variables | Business Usefulness                      | Limitations                                |
| ------------------- | ----------------------------------------------------------- | --- | --------------------- | ---------------------------------------- | ------------------------------------------ |
| Simple Model 1      | Marketing Spend                                             | 0.16724469 | Marketing Spend                   | Explains effect of marketing             | Ignores other factors                      |
| Simple Model 2      | Footfall                                                    | 0.73628534 | Footfall                   | Explains customer traffic impact         | Ignores operational variables              |
| Multiple Regression | Marketing, Footfall, Inventory, Customer Rating, Store Type | 0.84338181 | Marketing, Footfall, Inventory, Customer Rating, Store Type                   | Provides comprehensive business insights | Measures association rather than causation |

---

## Final Model Selection

The multiple regression model was selected as the preferred model because it incorporates several operational and business variables simultaneously. This approach reduces omitted-variable bias and provides a more realistic representation of the factors associated with monthly sales.

The final model also enables leadership to understand the relative contribution of each business factor while controlling for the influence of other variables.

---

## Limitations

* Regression identifies statistical association rather than cause-and-effect relationships.
* Important variables such as local competition, economic conditions, and promotional campaigns may not be included.
* Results depend on the quality and completeness of the available data.
* Business decisions should combine regression findings with managerial judgement.
