# IT Asset & License Management Framework

A practical, Excel-based framework designed for IT Managers to track hardware lifecycles and optimize software licensing costs.

## The Problem
IT departments frequently waste budget on unused software licenses ("shelfware") and lose track of hardware warranties, leading to unexpected replacement costs.

## The Solution
This repository provides two ready-to-use Excel dashboards and a methodology guide:
1. **[Hardware Asset Register](./01_Hardware_Asset_Register.xlsx) / ([.csv](./01_Hardware_Asset_Register.csv)):** Tracks device lifecycles and flags warranties expiring within 30 days.
2. **[Software License Tracker](./02_Software_License_Tracker.xlsx) / ([.csv](./02_Software_License_Tracker.csv)):** Calculates utilization percentages and flags software where less than 80% of purchased seats are actually used.
3. **[Methodology Guide](./00_IT_Asset_Management_Guide.md):** Best practices for hardware retirement, software negotiation, and audit readiness.

*Note on file formats: The templates are provided in both `.xlsx` (for live Excel formulas and dashboard formatting) and `.csv` (for quick plain-text viewing).*

## 📊 Sample View: Hardware Asset Register

| Asset ID | Device Type | Model | Assigned To | Status |
| :--- | :--- | :--- | :--- | :--- |
| AST-001 | Laptop | Dell Latitude 5420 | Piyush Gahlawat | 🟢 Active |
| AST-002 | Server | Dell PowerEdge R750 | Data Center | 🟢 Active |
| AST-003 | Laptop | MacBook Pro 14 | Jane Doe | 🔴 Retired |

## 📊 Sample View: Software License Tracker

| Software Name | Seats Purchased | Seats Used | Utilization % | Renewal Date |
| :--- | :--- | :--- | :--- | :--- |
| Microsoft 365 | 100 | 95 | 95% (Healthy) | 01/12/2026 |
| Jira Software | 50 | 30 | **60% (Shelfware)** | 15/03/2027 |
| Adobe Creative Cloud | 10 | 2 | **20% (Shelfware)** | 01/06/2026 |

## Author
Built by Piyush Gahlawat. For more of my work, see [Vendor Risk Framework](https://github.com/Piyush-Gahlawat/vendor-risk-framework).