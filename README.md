# Banking-Data-Analysis

Designed and developed an end-to-end Banking Data Analysis dashboard using Power BI, analyzing over 100,000 rows of real-world banking data related to customer transactions, frauds, and branch performance.

Built an optimized data model with relationships between Customer, Transaction, and Branch tables, ensuring efficient performance through proper normalization and Power Query transformations.

Implemented a Drill Through page using CustomerID as the filter field, enabling customer-level insights including transaction history, fraud patterns, average transaction amount, and behavior across channels.

Enabled users to right-click on a customer from the main dashboard and navigate to a dedicated drill-through report, enhancing interactivity and allowing deep-dive analysis for each customer.

Created key KPIs using DAX, such as:

Total Transactions

Fraudulent Transactions

Total Transaction Amount

Average Transaction per Customer

Fraud Percentage

Visualized fraud analysis using bar charts segmented by channel and gender, helping stakeholders quickly identify high-risk transaction mediums and customer demographics.

Designed interactive visuals including:

Donut and column charts for branch-wise and account-type distribution.

Line chart for fraud trend analysis over time.

Card visuals to summarize performance indicators.

Applied user-friendly slicers and filters (by BranchCity, TransactionType, Gender, Month) to allow flexible exploration of data across different dimensions.

Used SELECTEDVALUE() DAX function in the Drill Through page to display the selected customer's name and dynamically update visuals based on the filtered context.

Implemented conditional formatting and clean visual hierarchy to improve user experience and highlight key insights such as abnormal fraud rates or high-value transactions.

Ensured the dashboard is scalable, maintainable, and performance-optimized, with minimized visuals per page and reusability for monthly review and fraud monitoring.

