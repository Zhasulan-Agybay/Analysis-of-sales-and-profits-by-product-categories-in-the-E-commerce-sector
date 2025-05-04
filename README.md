# Analysis-of-sales-and-profits-by-product-categories-in-the-E-commerce-sector

# Dataset used: Online Retail from Kaggle.

# Analysis of sales and profits by product categories in the E-commerce sector.

## Objective
Understand which product categories bring the greatest profit, what the sales dynamics are and how they change depending on the season.

## Tools & Technologies
- Python (Pandas, Numpy, Matplotlib, Seaborn)
- STL, SARIMAX, Prophet, statsmodels.api
- Jupyter Notebook

## Key Insights
- Total revenue for the period: 3.97M.
- Categories A & B generate 47.3% of revenue.
- The UK remains the leading market.
- Q4 has the strongest seasonal effect.
- Discounted products show higher unit volumes and total sales.
- Category C, despite generating 52.7% of total sales, has relatively low profitability.
- Emerging sales growth is observed in Germany, France, and EIRE.

## Recommendations
- Re-evaluate Category C.
- Phase out or reposition low-margin products with weak performance.
- Implement targeted discounting for fast-moving or seasonal products.
- Avoid blanket discounting — instead.
- Use discounts tactically during low-season months.
- Launch category-focused campaigns in emerging markets.
- Use seasonal insights to adjust inventory levels in advance of Q4 demand surges.
- Introduce dynamic restocking models based on product velocity and regional demand trends.
- Collect additional data from low-performing markets to understand demand patterns and identify untapped opportunities.

## Visualizations
![ABC analysis](img/ABC analysis distribution of goods.png)
![Top 10 Products](img/Top 10 Products by Revenue.png)
![10 Bad Products](img/10 Bad Products by Revenue.png)
![STL](img/STL-decomposition.png)
![STL + SARIMA](img/STL + SARIMA Forecast.png)
![Sales trend in UK](img/Sales trend in UK.png)
![Sales trend in France](img/Sales trend in France.png)
![Sales trend in Germany](img/Sales trend in Germany.png)
![Sales trend in EIRE](img/Sales trend in EIRE.png)
![Revenue by country](img/Revenue by country.png)
![Distribution of sales](img/Distribution of sales with and without discounts.png)
![Distribution of units sold](img/Distribution of units sold with and without discount.png)
![Sales dynamics by month](img/Sales dynamics by month (with and without discount).png)
