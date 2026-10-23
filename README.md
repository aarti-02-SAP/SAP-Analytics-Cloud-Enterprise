# sap-analytics-cloud-enterprise-fpa
End-to-End Enterprise FP&amp;A, Revenue Operations &amp; Margin Leakage Optimization Solution in SAP Analytics Cloud (SAC)
# Global Enterprise FP&A & Margin Leakage Optimization in SAP Analytics Cloud (SAC)

An end-to-end Enterprise Performance Management, Financial Planning & Analysis (FP&A), and Revenue Operations solution built in **SAP Analytics Cloud (SAC)** for a multinational B2B technology distributor.

---

## 🏢 Business Context & Problem Statement
**Novalis Global Enterprises NV** is a $220M+ multinational manufacturer and B2B distributor operating across 14 legal entities in North America, EMEA, APAC, and LATAM. Despite an 11.2% top-line revenue growth in FY2025 YTD, the company experienced a **410 bps compression in Operating Profit (EBIT) margin**.

### Core Enterprise Challenges:
* **Severe Margin Leakage (-410 bps)**: Driven by unmonitored commercial contract discounting (averaging 18.4%) and unrecovered international freight surcharges (+320 bps).
* **FP&A Planning Latency (8 Weeks)**: Quarterly rolling forecasts and budgeting relied on disconnected spreadsheets with broken macro formulas and zero audit trails.
* **Overhead Opacity**: Over $42M in corporate HQ shared services (central IT, R&D, cyber-defense) sat unallocated across regional subsidiaries.

---

## 🛠️ SAP Analytics Cloud Architecture
* **Data Model**: Measure-based modeling incorporating dual-axis measures, parent-child legal entity hierarchies, and multi-currency exchange conversion.
* **Version Governance**: Rigorous separation of closed `Actuals`, approved corporate `Budget`, and collaborative `Rolling Forecast` horizons.
* **Interactivity**: Dynamic Story Filters and cross-widget **Linked Analysis** for real-time customer tier and subsidiary drill-downs.

---

## 📊 Solution Storyboard Overview

### Page 1: C-Suite Executive Overview & Digital Boardroom
* 4 KPI metric tiles (`Net Revenue`, `Gross Margin`, `Operating Profit`, `Commercial Discounts`).
* Dual-measure monthly revenue and profit trajectory trends (2024 through Q3 2025).
* Subsidiary revenue and profitability rankings alongside customer segment market share donut with live Linked Analysis.

### Page 2: Operational Margin Leakage Deep Dive
* SKU-level Margin Leakage Drivers chart isolating commercial discounts from freight cost burdens.
* Multi-dimensional SKU financial P&L breakdown table detailing Gross Sales through Operating Profit across all 14 product lines.

### Page 3: FP&A Planning & Rolling Forecast
* Comparative Multi-Version Planning Grid aligning `Actual` vs. `Budget` vs. `Forecast` side-by-side.
* Multi-year Revenue Trajectory curve tracking actuals into seasonal budget targets and rolling forecast projections (2024–2026), scaled in Millions.

---

## 📂 Repository Contents
* `/data/`: Raw transaction dataset (5,260 rows) and master dimension files.
* `/documentation/`: Full 9-page architecture functional specification (`sap_sac_enterprise_portfolio_project.pdf`) and live SAC 3-page export (`Novalis_Executive_Dashboard.pdf`).
* `/screenshots/`: High-resolution dashboard captures.

---

## 🏆 Key Business Impact
* Isolated **$12.4M** in commercial discount and logistics margin leakage across product lines.
* Reduced quarterly rolling forecast consolidation cycle time by **65%**.
* Established fully-loaded legal entity profitability across all 14 operating subsidiaries.
