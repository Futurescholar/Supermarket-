# Data Visualization Project Report

---
## Project Title
### Supermarket Sales Report

---
## Objective
### To evaluate the business performance over the last quarter and identify strategic opportunities to:
- Improve customer satisfaction
- Increase overall sales
- Boost profitability
- Understand the performance of each product category

---
## Problem Statement
- What actions can improve customer satisfaction?
- How can sales volume and revenue be increased?
- Which strategies will enhance profit margins?
- What is the performance breakdown by product category?

---
## Tools Used
- Power BI – For visualization and dashboard creation
- Excel – For data cleaning and preprocessing
- Dataset Source – Kaggle

---
## Visualization Approach
- Data was cleaned and preprocessed in Excel before being imported into Power BI.
- A table was created for measures in Power BI for better organization and ease of editing.
- KPI cards were created to highlight key metrics such as Total Revenue, Quantity Sold, Profit, and Tax Paid.
- Various bar and line charts were used to visualize revenue by City, Gender, Month, Customer Type, and Product Category.

### A dedicated Product Analysis Page was created to explore:
- Quantity sold per product line
- Average unit price
- Average customer ratings
- Profit by category
- Slicers for filters such as Gender, Month, Customer Type, City, Product Line, and Payment Type were added to allow dynamic interaction with the report.

---
## Key Observations
[Overview](./Screenshot%20(67))
[Product Insights](./Screenshot%20(68))
- Branch C (Naypyitaw) generated the highest revenue, outperforming Branches A (Yangon) and B (Mandalay).
- 7:00 PM was identified as the peak hour for revenue generation, suggesting higher customer activity in the evening.
- Member customers contributed more to revenue than non-members, indicating stronger purchasing behavior or loyalty among members.
- February recorded the lowest sales volume, with a notable dip compared to January and March.
- Each product category had a unique revenue peak time:
   * Food and Beverages: 7 PM
   * Electronics Accessories: 6 PM
   * Fashion Accessories: 1 PM
   * Health and Beauty: 2 PM
   * Home and Lifestyle: 5 PM
   * Sports and Travel: 7 PM
- Among Product Categories Food and Beverages:
  * Had the highest revenue
  * Enjoyed the highest profit share (17.38%)
  * Received the highest average rating (7.11)
- The Fashion Accessories and Sports and Travel lines had the highest average unit prices, while still contributing strongly to both profit and quantity sold.
- The lowest-rated product line was Home and Lifestyle (6.84), which may indicate room for improvement in product quality or customer experience.

---
## Summary of Findings
- The supermarket performs best in Branch C, especially in evening hours, with members being the most valuable customer segment.
- Food and Beverages is the top-performing category across all major KPIs: sales, rating, and profitability.
- February’s underperformance could indicate seasonal trends or marketing gaps.
- There’s an opportunity to optimize inventory and promotions around time-of-day trends and product-specific peak periods.
- Some categories (e.g., Home and Lifestyle) lag in customer satisfaction despite moderate sales, which could impact brand perception.

---
## Recommendations
### Maximize Peak Hour Sales:
- Reinforce staffing, stock levels, and promotional activity around 7 PM when traffic is highest.
- Experiment with flash sales or bundled offers during peak hours.
- Expand Membership Program:
- Members are clearly more valuable; incentivize sign-ups with loyalty points, referral bonuses, or tier-based discounts.
- Track engagement and offer personalized promotions based on member behavior.

### Target February Slump:
- Introduce promotional campaigns in February (e.g., Valentine’s Day discounts or limited-time offers).
- Re-engage customers with SMS/email marketing or social media ads during the period.

### Focus on High-Performing Categories:
- Prioritize marketing, placement, and variety in Food and Beverages, Sports and Travel, and Fashion Accessories.
- Use upselling and cross-selling techniques to grow basket sizes.

### Improve Low-Rated Categories:
- Conduct surveys or gather feedback on categories like Home and Lifestyle and Electronic Accessories.
- Explore quality enhancement or product replacements where applicable.

### Change Product Launch Timing:
- Schedule promotional activities and product launches around each product’s revenue peak time, as identified in the time-based charts.

### Geographic Customization:
- Replicate successful strategies from Branch C in other branches.
- Explore location-specific promotions based on customer preferences in Yangon and Mandalay.

---
## Technical Details
- All measures were dynamically created in Power BI for Revenue, Profit, Tax, and Quantity Sold.
- DAX formulas were used to define KPIs and derive average prices and ratings.
- Custom visuals and color themes were applied for readability and storytelling.
- Interactive filters ensure personalized insights based on selection (gender, month, payment, etc.).




