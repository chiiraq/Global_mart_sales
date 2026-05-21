**GlobalMart Sales Data Analysis Project**

**Overview**
This project is a data cleaning, transformation, and business intelligence exercise built around a fictional retail dataset called GlobalMart. The dataset contains sales transaction records across multiple U.S. regions, product categories, and time periods (2022–2024). The project is designed as a timed, hands-on assessment split into three core tasks: data cleaning, data organization, and quick business insights.

**What This Project Does**
The project takes a raw, messy sales dataset and transforms it into clean, analysis-ready data to derive actionable business insights. Specifically, it:
1.Cleans the raw data by removing duplicates, fixing inconsistent text entries, converting data types, and handling missing values.
2.Organizes the data by standardizing column names, creating derived columns (e.g., recalculating profit), and extracting date components.
3.Analyzes the cleaned data to calculate total sales, identify top-performing products, and summarize sales trends by month.

Technologies & Skills Utilised:
1.Excel / Spreadsheet manipulation
2.Data cleaning (deduplication, type conversion, missing value imputation)
3.Data transformation (column renaming, derived fields, date extraction)
4.Pivot tables & summarization
5.Business intelligence (KPI calculation, trend analysis)

   
  Here are the **concise key takeaways**:

---

## Major Pointers in the data  — GlobalMart Sales Data

### 1. West Region Dominates
The West region drives **67% of all sales** ($725K of $1.08M total), making GlobalMart heavily reliant on a single market. This concentration creates geographic risk — if West performance declines, the entire business suffers.

### 2. Office Supplies Is the Star Category
**Office Supplies generates 61% of revenue** ($667K) with the **highest profit margin at 67%**. It outperforms Furniture and Technology on both volume and profitability, making it the clear strategic priority.

### 3. One Outlier Skews Everything
A single **$500K "Paper response" sale** in December distorts monthly trends, product rankings, and sales distribution. The median transaction is only $502 — this outlier is 1,000x normal size and likely a data entry error.

### 4. Nearly Every Sale Is Profitable
**97.7% of transactions are profitable** (977 of 1,000). Only 23 sales lost money. This shows strong pricing discipline, though those 23 loss-makers warrant review to prevent repeat patterns.

### 5. Discounts Are High But Working
The **average discount is 24%** across all regions. Despite aggressive markdowns, profitability remains high. However, the West region achieves the highest sales with lower discounts (23%) than the East (26%), suggesting room to optimize discount strategy.

### 6. Technology Underperforms on Volume
**Technology has healthy margins (63%) but the lowest sales** ($156K vs. $667K for Office Supplies). It contributes just 14% of revenue despite competitive profitability — an opportunity to expand market share.

### 7. Data Quality Must Be Fixed First
The dataset contains **null strings, inconsistent text casing, missing values, and extreme outliers**. Any strategic decision made on uncleaned data risks being wrong. Clean the data before drawing conclusions.

### 8. Sales Are Driven by a Few Big Orders
The **average sale ($1,142) is more than double the median ($502)**, meaning a handful of large transactions inflate the average. Most orders are small — understand this distribution before forecasting revenue.

