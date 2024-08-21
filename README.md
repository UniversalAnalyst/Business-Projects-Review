# A Review of my Data Analytics Projects at Baymar and the Results

## Profit Margins Exploration & Findings

### Business Case
- Growth in company headcount and projects has introduced complexity, leading to potential financial inefficiencies.
- The need exists to identify key variables influencing profit margins to reduce inefficiencies.
- Monitoring and controlling high-impact variables can improve financial performance.

### Questions & Hypotheses
- **Which clients yield the most profits?**  
  Hypothesis: Long-standing clients due to established understanding of their processes.
- **Which products/instruments yield the most profits?**  
  Hypothesis: Older products due to better system knowledge.
- **Which types of work yield the most profits?**  
  Hypothesis: Knowledge work requiring experienced staff billed at higher rates.
- **Which types of work yield the least profits?**  
  Hypothesis: Manual work billed at lower rates.

### High-Level Exploratory Data Analysis (EDA)
- Accessed MySQL database via phpMyAdmin.
- Data from 2015-2021, exported to CSV.
- Pre-processed data in BigQuery, then visualized in Tableau.
- **Profit & Loss (P&L) Calculation**: PO Amount minus hours billed at client rate.

### Key Findings
- **High-profit clients**: Accel Diagnostics, Securaplane, HTG.
- **High-profit products**: AXDX, HE600, HTG.
- **High-profit work types**: Manufacturing services, machine shop.
- **Recommendation**: Simulate successful client characteristics to improve low-profit clients, negotiate better contracts, and scope projects for faster lead times.

### Challenges & Caveats
- Missing revenue sources (e.g., engineering change orders).
- Labor cost was based on billed rates, not actual expense rates.
- Results may not fully capture financial impact.

### Deeper Analysis
- Focused on identifying sources of high costs in engineering services projects.
- Investigated staff labor costs and task duration.
- **Results**: Staff selection impacts margins, with higher-paid staff on low-billed tasks reducing profitability.

### Recommendations
- Assign low-expense staff to low-billed tasks and high-expense staff to high-billed tasks.
- Adjust contracts to better estimate task hours.
- Monitor project spend and margins to pivot plans as needed.




## Financial & Project Dashboard Development
- **Objective**: Monitor project spend, resource allocation, and budget goal attainment.
- Configured QuickBooks ODBC integration and used Power Query in Power BI.
- Created dashboards to visualize project expenses, resource spend, and margins.

### Key Benefits
- Allows Management to identify spend rates and take action before budgets are unrecoverable.
- Ensures employees are working on appropriately billed tasks.
- Encourages investigation and action into project execution.

### Challenges in Dashboards
- Data input errors caused inaccuracies, resolved through correction and additional data transformations.
- Anonymity maintained by using billed rates instead of actual expense rates, leading to approximate financial insights.

