The objective of this project is to:
Generate a simulated paid search performance dataset (10,000+ records)
Calculate key marketing KPIs:
CTR (Click-Through Rate)
Conversion Rate
CPA (Cost per Acquisition)
ROAS (Return on Ad Spend)
Identify inefficient high-cost / low-ROAS keywords
Reallocate a portion of the budget to better-performing keywords
Estimate the projected improvement in ROAS & CPA after reallocation
This project is often used to demonstrate skills for Data Engineer, BI Engineer, and Marketing Analytics roles.
🛠 Technologies Used
Python
Pandas
NumPy
Google Colab
Matplotlib (optional for charts)
SQL Concepts (Group By, Aggregation, Filtering)
GitHub
dataset.csv                     # Simulated paid search dataset
paid_search_budget_optimizer.ipynb   # Full code (Google Colab)
README.md                       # Documentation
1. Dataset Simulation
Creates a realistic dataset with:
Keywords
Impressions
Clicks
Cost
Conversions
Revenue
Quality Score
Calculated KPIs
2. SQL Concepts Applied in Pandas
Group By Keyword
Aggregation
Calculating KPIs
Filtering inefficient segments
3. Keyword Budget Segmentation
Identifies:
High-cost keywords
Low-ROAS keywords
Produces a list of inefficient keywords for optimization.
4. Budget Reallocation Model
Simulates:
Moving 15% of budget from inefficient keywords
Reallocating to top-performing keywords
Estimating:
12% ROAS improvement
↓9% CPA reduction

Results Summary
After reallocation:
ROAS increases by approximately 12%
CPA decreases by approximately 9%
Budget becomes more efficient
Good demonstration of performance marketing analytics
How to Run the Project
Open the notebook: paid_search_budget_optimizer.ipynb
Run all cells in Google Colab
Upload your own dataset if needed
