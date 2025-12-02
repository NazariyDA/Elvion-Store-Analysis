#  <img width="45" height="45" alt="image" src="https://github.com/user-attachments/assets/8b922d7f-d06e-4189-a9d1-739f799f3e1d" /> Elvion Store Analysis (Sales and Profit Analysis) 
The sales and profit dashboard is designed to provide a clear understanding of business performance Elvion Store. It contains data on orders, customers, products, sales, profit, regions, and time periods (2021–2024). 

:pushpin: Data source and Interactive Dashboard: [Elvion Store Analysis](./Elvion%20Store%20Analysis.xlsx)

🧩 Used technologies: **MS Excel** with **Power Pivot** (data cleaning and transformation) 

### The main objectives of this dashboard are:
- **Analysis of sales performance and profit:** The dashboard allows you to track total sales, profit, and their dynamics by years, months, or categories. The goal is to assess business growth, identify peak periods, and determine seasonality.
- **Optimization of the product assortment:** With data on categories and subcategories, it is possible to analyze profitability. For example, you can identify profitable and unprofitable segments in order to adjust purchases or prices.
-  **Regional and customer analysis:** Data by states and customers helps identify key markets and loyal buyers. The goal is to focus marketing efforts, expand presence in profitable regions, or develop loyalty programs.
-  **Forecasting and planning:** With time-based data, you can build trends and forecast future sales or profit. This is useful for budgeting, inventory management, and identifying potential risks.

## <img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/2e00bec0-d629-4368-9657-90e933350f74" /> General overview
The database contains **8,314** sales records from **2021 to 2024**, with total sales amounting to **$ 1 928 888** and profit totaling **$ 247 962** . The data covers product categories (Furniture, Office Supplies, Technology), U.S. states, customers, and monthly/yearly trends.

## <img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/7eb2f23e-13d4-4b4b-be1c-edef8e7c8b44" /> The dashboard includes the following key features:
* **Key Metrics Overview:** Highlight total sales and total profit for quick performance snapshots. 
* **Profit by Year Chart:** Visualize yearly profit trends to identify growth opportunities.  
* **Sales Breakdown by Category:** Dive deep into sales distribution across categories. 
* **Customer Count by Year:** Analyze customer engagement trends with a detailed pie chart.  
* **Sales by State Map:** Understand your geographical performance with a sales heatmap.
* **Monthly Sales Trends:** Spot performance patterns with easy-to-read monthly trends.
* **Top 5 Customers Profits:** Identify and focus on your most valuable customers

<img width="1224" height="644" alt="image" src="https://github.com/user-attachments/assets/8c44fa02-07d9-4049-9462-91a6dc4e51b1" />

## <img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/6793dbc4-3d2d-4088-bf15-df94174bfd8f" /> Conclusions and Recommendations Based on the Elvion Dashboard Analysis:
* ### Annual Trends
Sales and profit increased from 2021 to 2023, with a slight decline in 2024 (possibly due to incomplete data). Profit per unit sold improved, indicating better efficiency.

| Year | Sales       | Profit      | Profit Change (YoY)        |
|------|------------|------------|---------------------------|
| 2021 |  $ 483,966 |  $ 49,556  | -                         |
| 2022 |  $ 470,532 |  $ 61,618  | +24%                      |
| 2023 |  $ 609,094 |  $ 81,786  | +33%                      |
| 2024 |  $ 365,294 |  $ 54,999  | -33% (incomplete year?)   |


<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** 2023 was the best year (with a 29% increase in sales). The decline in 2024 may be seasonal or require data verification.

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Analyze the growth factors of 2023 (e.g., marketing efforts or new products).

* ### Analysis by Categories and Subcategories
**The Technology category** leads in profit (17% of sales generates 49% of profit). **Office Supplie**s is stable, but **Furniture** has profitability issues.

| Category        | Sales      | Profit     | Profitability (%) |
| --------------- | ---------- | ---------- | ----------------- |
| Technology      |  $ 704,452 |  $ 121,861 | 17.3              |
| Office Supplies |  $ 602,093 |  $ 108,211 | 18.0              |
| Furniture       |  $ 622,342 |  $ 17,888  | 2.9               |


Top 5 subcategories by sales (with profit):

  | Subcategory | Sales      | Profit     |
| ----------- | ---------- | ---------- |
| Phones      |  $ 279,464 |  $ 37,562  |
| Chairs      |  $ 277,058 |  $ 21,710  |
| Storage     |  $ 190,679 |  $ 17,478  |
| Binders     |  $ 169,089 |  $ 30,231  |
| Tables      |  $ 167,672 |  $ -12,327 |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** Strengths: Copiers (sales 118,968; profit 43,622 — profitability 37%) and Accessories — high profit with low risk.
Issues: Tables and Bookcases are unprofitable (-12k and -2.4k profit).

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Review suppliers or prices for Furniture; Invest in Technology for scaling (especially Copiers/Phones) — high ROI. Avoid unprofitable subcategories in Furniture.


Subcategories Supplies and Fasteners — low sales but stable profit.

* ### Sales by States
The top 10 states generate ~80% of sales. California is the leader, but Eastern states (New York, Pennsylvania) are also strong.

| State        | Sales      |
| ------------ | ---------- |
| California   |  $ 390,145 |
| New York     |  $ 246,517 |
| Texas        |  $ 151,436 |
| Washington   |  $ 117,661 |
| Pennsylvania |  $ 95,494  |
| Florida      |  $ 79,303  |
| Illinois     |  $ 68,565  |
| Virginia     |  $ 67,825  |
| Michigan     |  $ 66,559  |
| Ohio         |  $ 66,407  |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** The West Coast (CA, WA) is a key market (over 500k in sales). States with low sales (e.g., Maine — 1.2k) may be underutilized.

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Expand marketing in top-performing states; investigate the reasons for low sales in underperforming regions (e.g., Arizona or Colorado).

* ### Top Customers by Profit
The top 5 customers generate ~10% of total profit, indicating a reliance on key buyers.

| Customer      | Profit   |
| ------------- | -------- |
| Tamara Chand  |  $ 8,981 |
| Raymond Buch  |  $ 6,939 |
| Sanjit Chand  |  $ 5,757 |
| Adrian Barton |  $ 5,202 |
| Martinez      |  $ 3,883 |

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** These customers are loyal and likely place large orders (e.g., Tamara Chand — possibly a corporate client).

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Implement loyalty programs for top customers; diversify the customer base to reduce risks.

* ###  Monthly Trends (Seasonality)
Sales peak in the fall/winter, with a low in winter/spring. This may indicate holiday seasons or budget cycles.

| Month | Sales      |
| ----- | ---------- |
| Jan   |  $ 94,924  |
| Feb   |  $ 59,640  |
| Mar   |  $ 205,005 |
| Apr   |  $ 137,480 |
| May   |  $ 155,028 |
| Jun   |  $ 152,718 |
| Jul   |  $ 147,238 |
| Aug   |  $ 159,043 |
| Sep   |  $ 219,783 |
| Oct   |  $ 122,546 |
| Nov   |  $ 234,013 |
| Dec   |  $ 241,464 |



<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/48c4ff08-2a9d-4d3c-9718-eee6f10e87a1" /> **Conclusions:** Peaks occur in Nov–Dec (holiday season) and Sep (back-to-school?). Low months (Jan–Feb) are opportunities for promotions.

<img width="15" height="15" alt="image" src="https://github.com/user-attachments/assets/f35489d1-c8a5-4471-9b95-d5fb263625ac" /> **Recommendation:** Plan inventory and marketing for Q3–Q4; analyze the causes of the March spike.







  





