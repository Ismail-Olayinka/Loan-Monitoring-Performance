# Loan Monitoring Performance 

A production grade loan monitoring solution built on Microsoft Excel
and Power BI, simulating the loan portfolio surveillance infrastructure used
by CBN licensed financial institutions in Nigeria.

## Project Summary

| Attribute | Detail |
|---|---|
| Portfolio Size | 30,000 loan records |
| Raw Data Columns | 29 fields per record |
| Principal Amount | ₦1.397 Trillion |
| Outstanding Balance | ₦732.17 Billion |
| Risk Grades | 5 (CBN/IFRS 9 framework) |
| Dashboards | 3 Power BI pages |
| DAX Measures | 10+ calculated KPIs |
| Tools | Microsoft Excel, Power BI, Power Query, DAX |

## Key Features

### Excel Risk Engine
- CBN five-grade loan classification 
- Risk Score model (0–100) per borrower based on DPD and collateral coverage
- Alert Flag: DPD > 30
- CBN provision calculation linked to central Assumptions sheet
- Collateral adequacy classification (Adequate / Partial / Insufficient / Unsecured)
- Exposure at Risk calculation netting collateral recovery value
- Days to Maturity tracking per loan

### Power BI Dashboard Suite

**Page 1 — Portfolio Overview** 
- NPL exposure by branch (Doubtful + Loss filtered)

**Page 2 — Loan Detail**

**Page 3 — Trend Analysis**

## Key Findings

1. At 17.2%, the portfolio NPL ratio is 3.44 times the CBN regulatory ceiling of 5% and 2.46 times the current Nigerian banking industry average of 7%, as reported by the CBN in its 2025. This represents a systemic credit quality failure that warrants board-level escalation. In a licensed institution.

2. 3,099 (10.3%) of the total loans are completely unsecured with zero collateral. A further 1,501 (5%) of the total loans use inventory as collateral, which are assets with distressed recovery rates.

3. Loans disbursed in 2024 show higher proportions of Substandard and Doubtful classifications compared to 2021, 2022 and 2023; suggesting possible loosening of underwriting standards during the disbursement process.

4. Port Harcourt has the highest loans lost with 11.74% outstanding loan balance. Calabar has the highest of doubtful and lost loans with 11.63% of outstanding loan balance.
