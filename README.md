# FashionWave Sales Analysis – Power BI Project

fe653fd3-c9ce-4594-89e5-a5bc4ae…

## 📌 Project Overview

FashionWave is a mid-sized retail chain operating 50 stores across India. Recently, the company noticed stagnant weekend sales, which is concerning because weekends typically drive higher footfall and revenue.
This project analyzes multi-year sales data and provides insights to increase weekend performance, optimize discount strategy, and improve store-level profitability.

🎯 Project Objectives

Increase weekend sales by 15% in the next quarter

Improve product-level profitability

Make data-driven recommendations for discount optimization

Identify underperforming stores and customer behavior trends

📂 Dataset Description

Source: Kaggle

Time Period: 2023–2025

Rows: 15,000

Columns: 17

Key Fields:
Invoice No, Date, Month, Day, DayType (Weekday/Weekend), Quarter, StoreID, ProductID, Category, Quantity, UnitPrice, Discount, CostPerUnit, CustomerType, PaymentMode, Revenue, Total Cost

🛠 Tools Used

Microsoft Excel: Initial data cleaning & exploration

Power BI: Data modeling, DAX measures, and dashboard creation

🔧 Data Preparation & Modeling

Steps followed in the analysis:

✔ Data Cleaning (Power Query)

Removed duplicates

Fixed incorrect data types

Handled missing values (Discount %, CustomerType)

Created new columns:

DayType (Weekday/Weekend)

WeekStartDate

Year Quarter

✔ Data Modeling

Designed Star Schema

FactSales table

Dimension tables: Date, Store, Product

✔ DAX Measures

Key measures created:

Total Revenue

Total Profit

Profit Before Discount

Profit After Discount

Total Orders

Average Order Value (AOV)

Weekend Revenue

Weekday Revenue

✔ Visualizations

Interactive dashboard showing:

Revenue & Profit by Category

Weekend vs Weekday Revenue

Store-wise Weekly Revenue

Profit before vs after discount

Customer segmentation (New vs Returning)

📊 Key Insights
1️⃣ Revenue & Profit by Category

Accessories generate the highest revenue (~₹83M) and strong profit

Shoes contribute ~₹65M

Clothing is the lowest (~₹46M)

Discounts significantly reduce profits, especially for Accessories & Shoes

2️⃣ Weekend vs Weekday Sales

Weekdays contribute ~65–66% of total revenue

Weekends contribute only ~34–35%, confirming stagnation

3️⃣ Store Performance

Stores like STR001, STR003, STR005 lead consistently

Multiple stores show weak performance → need for store-specific improvements

4️⃣ Discount Impact

Profit Before Discount: ~₹159.32M

Profit After Discount: ~₹139.96M

Heavy discounting reduces profit margins significantly

5️⃣ Customer Segmentation

Returning customers show:

Higher AOV

More consistent spending

Strong potential for loyalty campaigns

🧾 Answers to Business Questions
✔ Which categories perform best?

Accessories > Shoes > Clothing in revenue & profit.

✔ How do weekend sales compare?

Weekends underperform at only 34–35% of revenue.

✔ Impact of discounting?

Profit drops ~₹20M after discounts → discounts must be more targeted.

✔ Which stores are underperforming?

Multiple stores have low weekly revenue → possibly due to local demand, poor merchandising, or weak promotion.

✔ Can customers be segmented?

Yes — New vs Returning.
Returning customers are more profitable; loyalty strategies can be effective.

✔ Overall performance?

Total Revenue: ₹136.76M

Total Profit: ₹99.37M

Total Orders: ~11K

📝 Recommendations
⭐ 1. Boost Weekend Performance

Weekend-only offers

Combo deals

In-store events

Targeted digital promotions

⭐ 2. Optimize Discount Strategy

Reduce blanket discounting

Focus discounts on slow-moving items

Control discount depth to protect margins

⭐ 3. Improve Low-Performing Stores

Store audits

Staff training

Better visual merchandising

Localized marketing

⭐ 4. Promote High-Margin Categories

Upsell Accessories at checkout

Cross-sell related items

⭐ 5. Strengthen Loyalty Programs

Personalized SMS/email offers

Reward returning customers

Encourage repeat visits

⭐ 6. Continuous Monitoring

Keep dashboard refreshed

Track weekday vs weekend trends

Monitor discount-performance impact

🏁 Conclusion

The analysis reveals that while FashionWave’s overall sales are healthy, weekend sales remain a major weakness. Profitability is affected by ineffective discounting and variation in store performance.
By applying data-driven strategies—optimizing discounts, strengthening weekend promotions, and focusing on underperforming stores—the company can realistically achieve a 15% improvement in weekend revenue.
The Power BI dashboard enables ongoing monitoring and helps management make informed decisions.
