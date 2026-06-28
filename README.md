# Part 3: Regression-Based Business Insights & Model Interpretation

## Student Details

**Name:** Divyansh Goel
**Student ID:**bitsom_ba_25111001

---

# Business Problem Summary

The objective of this project is to identify the business factors that are most strongly associated with monthly sales across retail stores using regression analysis. The analysis helps management understand which operational variables have the greatest impact on sales performance and supports better business decision-making.

---

# Dataset Description

The dataset contains monthly business performance information for multiple retail stores.

It includes variables such as:

* Marketing Spend
* Footfall
* Average Discount Percentage
* Staff Count
* Inventory Availability Percentage
* Customer Rating
* Holiday Flag
* Region
* Monthly Sales
* Monthly Profit

The dataset was provided as part of the assignment.

---

# Dependent Variable

* Monthly Sales

---

# Independent Variables

The following variables were used for regression analysis:

* Marketing Spend
* Footfall
* Average Discount Percentage
* Staff Count
* Inventory Availability Percentage

---

# Regression Approach

The project includes:

* Data cleaning and preparation
* Creation of dummy variables for categorical data
* Two simple linear regression models
* One multiple regression model
* Model comparison
* Residual analysis
* Business interpretation of regression results

Regression analysis was performed using Microsoft Excel's Data Analysis ToolPak.

---

# Dummy Variable Approach

Dummy variables were created for the Region variable.

The reference category used was **North**, while dummy variables were created for:

* Region South
* Region East
* Region West

This avoids the dummy variable trap and allows meaningful interpretation of categorical effects.

---

# Model Comparison Summary

Three regression models were developed:

1. Simple Regression using Marketing Spend
2. Simple Regression using Footfall
3. Multiple Regression using Marketing Spend, Footfall, Average Discount Percentage, Staff Count, and Inventory Availability Percentage

The multiple regression model produced the highest explanatory power with an R² value of approximately **0.81**, making it the preferred model.

---

# Final Model Selected

The multiple regression model was selected because it considers multiple business drivers simultaneously and explains a large proportion of the variation in monthly sales.

---

# Business Recommendation

The analysis indicates that marketing spend, customer footfall, staff count, and inventory availability are positively associated with monthly sales. Management should prioritize investment in these areas to improve store performance. Discount strategies should be monitored carefully to ensure they improve revenue without unnecessarily reducing profitability.

Regression analysis identifies statistical relationships but does not by itself prove causation. Business decisions should therefore combine regression findings with operational experience and market knowledge.

---

# Assumptions and Limitations

* Regression measures association, not causation.
* Some business factors affecting sales may not be included in the dataset.
* The model assumes linear relationships between variables.
* Results are dependent on the quality and completeness of the dataset.

---

# Tools Used

* Microsoft Excel
* Excel Data Analysis ToolPak
* GitHub
* Markdown

---

# Repository Structure

```
part3_regression_insights/
│
├── data/
├── analysis/
├── outputs/
├── screenshots/
└── README.md
```

---

# Screenshots Included

* simple_regression_output.png
* multiple_regression_output.png
* residuals_preview.png
* model_comparison_preview.png

---

# Conclusion

The regression analysis demonstrates that multiple operational and business variables influence monthly sales. The multiple regression model provides the most useful insights for business decision-making and can support data-driven planning for marketing, staffing, inventory management, and store performance improvement.
