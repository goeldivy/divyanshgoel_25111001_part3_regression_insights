# Model Equations

## Simple Regression Model 1
Monthly Sales = Intercept + (Marketing Spend × Coefficient)

This model estimates monthly sales using only marketing spend.

## Simple Regression Model 2
Monthly Sales = Intercept + (Footfall × Coefficient)

This model estimates monthly sales using only store footfall.

## Multiple Regression Model

Monthly Sales = Intercept
+ (Marketing Spend × β1)
+ (Footfall × β2)
+ (Average Discount % × β3)
+ (Staff Count × β4)
+ (Inventory Availability % × β5)

## Coefficient Explanation

- Marketing Spend: Expected change in monthly sales for each unit increase in marketing spend.
- Footfall: Expected change in monthly sales for each additional customer visit.
- Average Discount %: Measures the impact of discounts on sales.
- Staff Count: Shows how staffing levels relate to sales.
- Inventory Availability %: Indicates how stock availability influences sales.

## Dummy Variable

Holiday Flag (0 = No Holiday, 1 = Holiday)

Reference Category:
Non-Holiday (0)

## Final Model Selected

The multiple regression model was selected because it explains monthly sales using several business factors and provides better predictive performance than the simple regression models.