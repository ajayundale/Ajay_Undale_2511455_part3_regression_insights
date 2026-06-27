# Regression Model Equations

## Simple Regression Model 1

**Dependent Variable**

Monthly Sales

**Independent Variable**

Marketing Spend

### Equation

> Monthly Sales = **[Intercept] + [Coefficient × Marketing Spend]**

### Interpretation

The marketing spend coefficient represents the expected change in monthly sales associated with a one-unit increase in marketing expenditure.

---

## Simple Regression Model 2

**Dependent Variable**

Monthly Sales

**Independent Variable**

Footfall

### Equation

> Monthly Sales = **[Intercept] + [Coefficient × Footfall]**

### Interpretation

The footfall coefficient indicates the expected increase in monthly sales associated with one additional customer visiting the store.

---

## Multiple Regression Model

### Equation

Monthly Sales =

**Intercept**

* Marketing Spend × **[Coefficient]**

* Footfall × **[Coefficient]**

* Inventory Availability × **[Coefficient]**

* Customer Rating × **[Coefficient]**

---

## Interpretation of Coefficients

### Marketing Spend

Represents the expected increase in monthly sales associated with additional marketing investment while holding all other variables constant.

### Footfall

Measures the relationship between customer traffic and monthly sales.

### Inventory Availability

Represents the expected increase in sales associated with improved product availability.

### Customer Rating

Measures whether better customer satisfaction is associated with higher monthly sales.


---

## Dummy Variable Approach

The categorical variable **Store Type** was converted into dummy variables.

Reference Category:

**Airport**

Dummy Variables Created for Store Types:

* High Rise
* Mall
* Residential

The reference category was excluded from the regression model to avoid perfect multicollinearity (Dummy Variable Trap).

---

## Final Model Selected

The multiple regression model was selected because it produced the highest explanatory power and incorporated both operational and store-format variables.

This model provides more comprehensive business insights than individual simple regression models.
