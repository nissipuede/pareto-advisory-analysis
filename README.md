# 2025 Pareto Advisory LLC: Regional & Macro Insights for Small Businesses

This repository contains the Python analysis scripts and data visualizations developed under Pareto Advisory LLC, which engages with small businesses to interpret local, regional, and macroeconomic trends. The goal is to identify how key economic indicators—such as cross-border activity, GDP composition, and currency strength—relate to local business conditions and operational outcomes.

# Research Summary

- **Purpose**: To provide data-driven insights to small business owners by connecting their operational patterns to the broader economic environment.
- **Approach**: Each analysis uses publicly available macroeconomic and regional datasets (from FRED, BEA, and U.S. Customs and Border Protection) to explore trends in trade flows, GDP growth drivers, and monetary conditions. Custom visualization modules—developed in-house (pareto_linechart and pareto_clustered)—standardize presentation and support business briefings and advisory reports.
- **Objective**: Empower regional firms, especially those operating in South Texas and the broader Rio Grande Valley (RGV), to make informed decisions based on statistically grounded associations between local economic indicators (e.g., unemployment, wage growth, border crossings) and broader macroeconomic forces.

# Data Scope
Primary Data Sources:
	•	U.S. Customs and Border Protection (CBP) — Traveler & Conveyance Statistics
	•	Bureau of Economic Analysis (BEA) — Real GDP and Expenditure Components
	•	Federal Reserve Economic Data (FRED) — Real Broad Dollar Index, Inflation Indicators

Coverage Period:
2015–2025, with emphasis on recent 24–36 months for near-term trend analysis.

## Repository Structure

| File                                 | Description |
|--------------------------------------|-------------|
| `CPB – Traveler and Conveyances Trends` | Analyzes monthly traveler and vehicle crossings through Rio Grande Valley (RGV) ports of entry. Produces time-series charts for total entries, month-over-month and year-over-year changes, and a 12-month rolling sum to identify trade and mobility cycles.|
| `Quarterly Contributions & Real GDP Growth – Annual Rate` | Uses BEA/FRED data to decompose U.S. real GDP growth into contributions from consumption, investment, government spending, and net exports. Highlights which sectors are driving recent economic expansion or contraction.|
| `U.S. Dollar Analysis` | Examines movements in the real broad dollar index and its relationship with inflation (PCE and Core CPI). Explores how dollar strength cycles correspond with monetary policy shifts and global capital flows.|

## Note on Data Availability

All data are drawn from publicly available government sources:
	•	FRED Economic Database (Federal Reserve Bank of St. Louis)
	•	BEA National Accounts (Bureau of Economic Analysis)
	•	CBP Traveler & Conveyance Statistics (U.S. Customs and Border Protection)

Each script fetches or reads data directly from these sources. Users can replicate analyses by running the included scripts with valid FRED API credentials.

## Methods Summary
- **Software**: Python 3.11
- **Libraries & Tools**: pandas, numpy, fredapi, matplotlib, custom Pareto plotting modules (pareto_linechart, pareto_clustered)
- **Techniques**:
	•	Time-series aggregation and rolling window analysis
	•	Percentage change (MoM, YoY) and contribution decomposition
	•	Dual-axis visualizations for comparative trend analysis
	•	Custom scaling logic for readability and interpretability

## Author

**Nissi Cantu**  
Master of Public Policy & Master of Business Administration  
Georgetown University  
📧 nc809@georgetown.edu  
🔗 [LinkedIn](https://www.linkedin.com/in/nissi-cantu/)
