TASK - 1
Comprehensive Data Cleaning Report (Using Excel)

As part of the data preparation process, I carried out a series of data cleaning tasks in Excel to ensure the dataset is accurate, consistent, and analysis-ready. Below are the key steps I followed:

Identification and Handling of Missing Values
I used Excel’s filter functions to identify missing or blank entries across key columns. Depending on the nature of the data, I either removed incomplete rows or flagged them for further review. This step was crucial in ensuring that no invalid or misleading records affect downstream analysis.

Removal of Duplicate Records
To prevent redundancy and potential skewing of insights, I utilized Excel’s built-in “Remove Duplicates” feature. This helped in eliminating repeated entries based on key identifiers, preserving only the most relevant and unique data.

Standardization of Text Fields
I cleaned and standardized textual data, particularly fields like gender, country names, and category labels. This included unifying variations (e.g., "Male" vs. "male", or "USA" vs. "United States") to a consistent format, which improves grouping and filtering accuracy during analysis.

Date Format Normalization
All date columns were converted into a consistent format (dd-mm-yyyy). This ensures uniformity across records and allows for more effective sorting, filtering, and time-based analysis.

Column Header Cleanup
To enhance readability and consistency, I reformatted column headers by renaming them to lowercase and removing any spaces or special characters. For example, “Date of Birth” became “date_of_birth”. This step also prepares the data for easier import into other tools if needed.

Data Type Verification and Correction
I reviewed each column to confirm that the data types were appropriate. For instance, age fields were set to numeric formats, while date fields were validated to ensure they were properly recognized as date objects in Excel. Any incorrect formats were corrected to align with their intended data types.


TASK - 2


1. Sales vs Profit by Region (Stacked Bar Chart)
Insight: The West region has high sales but low profit, likely due to high discounts or low-margin products.

This helps identify where revenue is not turning into profit.

2. Sales Trend Over Time (Line Chart)
Insight: Sales show a seasonal spike during Q4 (October–December) each year, indicating strong holiday performance.

Businesses can plan inventory and marketing around this trend.

3. Top & Bottom Performing Sub-Categories by Profit (Bar Chart)
Insight: While categories like Copiers are highly profitable, others like Tables and Bookcases show negative profit.

These underperforming areas may need pricing or product changes.

4. Segment-wise Profitability (Donut Chart)
Insight: The Corporate segment is the most profitable, while Home Office lags behind.

Targeted campaigns can be created to boost engagement with underperforming segments.

5. Profit vs Average Discount by Category (Clustered Column Chart)
Insight: The Furniture category offers the highest average discounts, yet returns lowest profit.

Consider reducing discount rates to improve profit margins.

 Business Conclusion:
The data reveals that sales alone are not enough — profit varies widely by region, category, and customer segment. Strategic adjustments in discount policies, product focus, and marketing can help improve overall profitability.

 Task 3 - SQL for Data Analysis

 Objective - 
Use SQL to analyze an eCommerce dataset, perform queries, and demonstrate key SQL concepts including:
- SELECT, WHERE, ORDER BY, GROUP BY
- JOINS (INNER, LEFT)
- Subqueries
- Aggregate functions (SUM, AVG)
- Creating Views
- Query optimization with Indexes


 Tools Used -
- MySQL Workbench
- Dataset: project1_df.csv (eCommerce transactions)


 Files Included -
- task3.sql: Contains all SQL queries as per task requirements.
- output.pdf: Folder containing output screenshots of executed queries.
- README.md: Explanation of task and queries performed.



Summary of Queries

a. SELECT, WHERE, ORDER BY, GROUP BY
- Filtered male customers and sorted by Net Amount
- Grouped data by Age Group to get average Net Amount

b. JOINS
- Created a mock `discount_campaigns` table
- Demonstrated INNER JOIN and LEFT JOIN with `project1_df`

c. Subqueries
- Retrieved customers who spent more than the average Net Amount

d. Aggregate Functions
- SUM of Discount Amount by Location
- AVG Gross Amount by Product Category

 e. Views
- Created a view `High_Value_Customers` for customers who spent more than 5000

 f. Indexes
- Created indexes on `Gender` and `Discount Name` for query performance optimization
