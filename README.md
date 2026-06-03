Welcome to my Decision Science portfolio. This repository contains end-to-end data analytics and machine learning projects focused on translating raw data into actionable business strategies.

The projects below demonstrate proficiency in Data Engineering (Python, Pandas), Exploratory Data Analysis (EDA), Predictive Modeling (Scikit-Learn), and Prescriptive Analytics (Power BI, DAX).

🛒 Project 1: Retail Profitability & Discount Optimization Engine
Files: reatil_performance_analysis.ipynb, Retail_Dashboard.pbix
Status: Completed
<img width="1071" height="736" alt="image" src="https://github.com/user-attachments/assets/6cea12b6-0255-49b2-9750-0ba34443ac84" />
<img width="1080" height="174" alt="image" src="https://github.com/user-attachments/assets/d2cc341c-fcda-48cc-8776-3c1f20b81a02" />
<img width="1069" height="286" alt="image" src="https://github.com/user-attachments/assets/e8ae2f2d-6667-4c71-a02b-a9b11d052382" />
<img width="1062" height="284" alt="image" src="https://github.com/user-attachments/assets/15bbdfe7-cf68-4f2f-ba3f-d2b73cf0c17c" />
https://github.com/user-attachments/assets/1d3f6455-80a9-4a48-8370-97bf12a077bc





📈 Business Problem
A global retail superstore was experiencing healthy top-line revenue growth but suffering from stagnant and negative bottom-line profitability in key segments. The objective of this project was to diagnose the root cause of the profit bleed and build a prescriptive tool to optimize future pricing strategies.

🛠️ Methodology & Execution
Data Validation & Cleaning (Python):

Imported and audited raw transactional data using pandas.

Standardized geographic data types and corrected locale-specific date formatting errors to ensure a robust downstream ETL pipeline.

Diagnostic Analytics (Power BI):

Utilized an AI-driven Decomposition Tree to perform Root Cause Analysis (RCA), isolating Furniture (specifically Tables and Bookcases) as the primary drivers of corporate profit loss.

Developed a Scatter Plot Diagnostic mapping Average Discount % against Profit Margin %, visually proving that structural unprofitability begins when discounts exceed the 20% threshold.

Prescriptive Analytics (The Decision Engine):

Engineered a dynamic "What-If" Simulator using a DAX SUMX row-context iterator. This allows executives to adjust a "Maximum Discount Cap" slider and instantly visualize recovered simulated profit.

Built an Action Matrix using conditional DAX logic to automatically output text-based business recommendations (e.g., "Cap Discounts" vs. "Audit Supplier Costs") for the bottom 5 underperforming sub-categories.
