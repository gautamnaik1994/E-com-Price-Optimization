# E-commerce Price Optimization

<center> <img src="./ecommerce-price-optimization.png"> </center>

Blog Link: [https://www.gautamnaik.com/blog/ecommerce-price-optimization/](https://www.gautamnaik.com/blog/ecommerce-price-optimization/)

**Business Problem**

TrendElite is a clothing retailer specializing in a diverse selection of apparel and accessories, operating both physical stores and an online e-commerce platform. To enhance its revenue and market competitiveness, the company aims to optimize its pricing strategy.

TrendElite faces several challenges in effectively pricing its products.

- Competitive Landscape: With numerous rivals offering similar products, the retail industry is highly competitive. TrendElite aims to stand out by offering attractive prices while ensuring profitability.

- Inventory Management: Ensuring effective inventory management is vital for TrendElite, as pricing strategies must balance supply and demand. Optimizing prices based on inventory levels can help prevent overstocking or understocking of products.

- Seasonal and Trend Variations: The fashion industry's rapid trend changes and fluctuating demand throughout the year present challenges for TrendElite. Adjusting prices to reflect seasonal and trend shifts is crucial to capitalize on sales opportunities.

**Solution**

Price Optimization can be used for tacking above challenges. We will be trying the following strategies

- Demand based pricing : The demand-based pricing strategy involves analyzing the demand for each product over time
to determine the optimal price for each product. The strategy involves setting a base
price for each product, and then adjusting the price based on the demand for the product.

- Competitor based pricing : The competitor-based pricing strategy involves analyzing the prices of competitors for
the same product and adjusting the price based on the competitor’s pricing.

- Price elasticity based pricing : The price elasticity-based pricing strategy involves analyzing the price elasticity of
each product to determine the optimal price for each product. The strategy involves
setting a base price for each product, and then adjusting the price based on the
price elasticity of the product.

**Metric**

We will use amount of revenue earned as a metric

**Dataset**

| Field                      | Description                                                                                   |
|----------------------------|-----------------------------------------------------------------------------------------------|
| product_id                 | A unique identifier for each product in the dataset.                                          |
| product_category_name      | The name of the product category to which the product belongs.                                |
| month_year                 | The month and year of the retail transaction or data recording.                                |
| qty                        | The quantity of the product sold or purchased in a given transaction.                          |
| total_price                | The total price of the product, including any applicable taxes or discounts. Calculated using qty*unit_price |
| freight_price              | The average freight price associated with the product.                                         |
| unit_price                 | The average unit price of a single unit of the product.                                        |
| product_name_length       | The length of the product name in terms of the number of characters.                           |
| product_description_length| The length of the product description in terms of the number of characters.                    |
| product_photos_qty        | The number of photos available for the product in the dataset.                                  |
| product_weight_g           | The weight of the product in grams.                                                            |
| product_score              | Average product rating associated with the product’s quality, popularity, or other relevant factors. |
| customers                  | The number of customers who purchased the product in a given category.                          |
| weekday                    | Number of weekdays in that month.                                                              |
| weekend                    | Number of weekends in that month.                                                              |
| holiday                    | Number of holidays in that month.                                                              |
| month                      | The month in which the transaction occurred.                                                   |
| year                       | The year in which the transaction occurred.                                                    |
| s                          | The effect of seasonality.                                                                     |
| Volume                     | Product Volume                                                                                 |
| Comp_1                     | Competitor1 price                                                                             |
| Ps1                        | Competitor1 product rating                                                                    |
| Fp1                        | Competitor1 freight price                                                                     |
| Comp_2                     | Competitor2 price                                                                             |
| Ps2                        | Competitor2 product rating                                                                    |
| Fp2                        | Competitor2 freight price                                                                     |
| Comp_3                     | Competitor3 price                                                                             |
| Ps3                        | Competitor3 product rating                                                                    |
| Fp3                        | Competitor3 freight price                                                                     |
| Lag_price                  | Previous month price of the product.                                                          |

**Recommendations**

- Pricing Strategy

  - In terms of pricing strategy, the Price Elasticity to Demand strategy seems most effective. This strategy is completely based on customer demand and reaction to change in price.
  - In this strategy, we have only changed the prices of products that are Inelastic, i.e. the products who change in price does not affect customer demand.
  - This also resulted in higher sales for all the months.

- Product Related

  - Holidays are extremely important. Months with higher number of holidays have higher sales.  
  - Due to higher number of customers during holidays, new products can be introduced to increase awareness.
  - Product description length should be around 1000 characters.
