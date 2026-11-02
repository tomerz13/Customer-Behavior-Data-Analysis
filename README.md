# Customer Shopping Behavior Analysis 🛒

## Executive Summary:

Using Python, SQL Server, and Data Visualization tools, I analyzed a dataset of 3,900 retail transactions to uncover customer spending patterns and identify opportunities for revenue growth. After identifying that the largest untapped revenue source lies in converting highly active shoppers into subscribers, and noticing significant margin risks due to high discount dependency on specific items, I recommend that the marketing and sales teams implement a few strategic adjustments:

Target repeat buyers with exclusive subscription tier perks.

Tighten discount policies on specific high-dependency product categories.

Reallocate marketing spend towards high-value demographic cohorts.

Number Impact: Successfully converting the identified pool of repeat non-subscribers could tap into $170k+ of existing segment revenue, while optimizing margins on items with a nearly 50% discount rate.

## Business Problem:

Consistent recurring revenue is essential for long-term retail growth, yet stakeholders have noticed that subscription enrollment is lagging despite high overall sales volume. Furthermore, there is growing concern that heavy reliance on promotional codes is eroding profit margins on popular items.

How can we segment our customer base to determine who our most loyal (but unsubscribed) customers are, and how can we optimize our discount strategies without losing purchase volume?

<img width="875" height="669" alt="image" src="https://github.com/user-attachments/assets/1a6efb60-ec02-410e-9290-1e997f036ed8" />



## Methodology (Skills):

Python: pandas (Data loading, cleaning, handling missing values in review ratings), Feature Engineering (creating age_group bins and mapping purchase_frequency_days), SQLAlchemy (Database connection and ETL process to SQL Server).

SQL Server: CTEs (Common Table Expressions), Window Functions (ROW_NUMBER), Aggregate Functions (SUM, AVG), CASE statements for customer segmentation, and JOIN/Grouping logic.

Data Visualization & Strategy: Executive reporting, KPI tracking, and translating statistical analysis into actionable business recommendations.

## Results & Business Recommendation:

By staging the cleaned data in SQL Server and analyzing the results, I was able to give stakeholders clear visibility into customer demographics and product performance. This analysis showed that a massive 73% of the customers are not subscribed, yet 2,518 of those unsubscribed users are repeat buyers (having made more than 5 previous purchases). Additionally, I found that the Male segment drives 68% of total revenue ($157k+), and products like Hats and Sneakers are heavily reliant on discounts (approx. 50% discount rate).

<img width="1309" height="732" alt="image" src="https://github.com/user-attachments/assets/dd61ec2b-5cef-4374-b188-8f6775cc76e6" />


Because the biggest revenue impacts will likely come from increasing subscription rates and protecting profit margins, I recommend the following business adjustments:

Boost Subscriptions: Send targeted email/text campaigns to the 2,518 repeat non-subscribers highlighting exclusive tier perks to drive recurring revenue.

Revise Discount Policy: Tighten promotional thresholds on Hats, Sneakers, and Coats to balance sales volume against margin erosion.

Expand Loyalty Paths: Build retention campaigns targeting the 701 "Returning" buyers to move them smoothly into the "Loyal" segment (which currently makes up nearly 80% of the base).

Targeted Marketing: Focus advertising spend heavily on the Young Adult cohort and Male segment, prioritizing users who opt for express shipping.

I believe these adjustments will best tackle the current margin risks, increase overall recurring revenue, and maximize the lifetime value (LTV) of our existing active shoppers.

## Next Steps:

For upcoming projects, I would explore the following:

A/B Test Marketing Copy: Run A/B tests on the promotional emails sent to the 2,518 prime targets to see which incentives (e.g., free shipping vs. flat percentage off) drive higher subscription conversions.

Time-Series / Seasonal Analysis: Analyze purchase timestamps to see if discount dependency heavily correlates with specific seasons (e.g., Winter vs. Spring), allowing for more dynamic pricing models.

Measure Conversion Rates: Track the open and click-through rates of the newly proposed loyalty campaigns to measure direct ROI.
