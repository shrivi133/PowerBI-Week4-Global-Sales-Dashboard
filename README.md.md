# Power BI Week 4 — Dashboard Design & Publishing (Global Sales Dashboard)

## Project Overview
This repository contains the **Week 4: Dashboard Design & Publishing** Power BI assignment built on the **Global Superstore 2022 Dataset**. It covers interactive visual design, drill-through & bookmarks, custom corporate theme branding, and publishing to **Power BI Service**.

---

## Implemented Dashboard Visuals & Features

### 1. Executive KPIs (Project Task)
* **Total Sales:** `$20,250.00`
* **Total Profit:** `$4,895.00`
* **Average Discount:** `6.25%`

### 2. Core Dashboard Visuals (4 Required Visuals)
1. **Sales by Region (Map Visual):** Geographic filled/bubble map displaying revenue distribution across `North America`, `Europe`, `Asia Pacific`, `Latin America`, and `Middle East & Africa`.
2. **Category-wise Profit (Clustered Bar Chart):** Compares profitability across `Technology` (`$3,020.00`), `Furniture` (`$1,320.00`), and `Office Supplies` (`$555.00`).
3. **Monthly Revenue Trend (Line Chart):** Tracks Jan–Dec 2022 monthly revenue progression with interactive hover tooltips.
4. **Top 5 Customers (Table Visual):** Top-N filtered table highlighting the highest-revenue customers (`Aarav Sharma`, `Liam O'Connor`, `Mateo Silva`, `Sophia Miller`, `Kenji Takahashi`).

### 3. Slicers, Branding & Publishing
* **Interactive Slicers:** Configured slicers for **Year** (`2022`), **Segment** (`Corporate`, `Consumer`, `Home Office`), and **Region**.
* **Navigation & Interactivity:** Added drill-through page for Customer/Product order details and Bookmarks for "Reset Filters" and "Executive View".
* **Theme & Logo Branding:** Applied custom corporate JSON theme (`theme_branding.json`) with brand colors (`#0F4C81`, `#00A896`, `#F4A261`) and header logo placement.
* **Power BI Service Publishing:** Published `.pbix` report to **My Workspace** in Power BI Service (`app.powerbi.com`) with shareable report link enabled.

---

## Analytical Summary

### Sales & Profit by Region (Top Regions)
| Rank | Region | Total Sales ($) | Total Profit ($) |
| :--- | :--- | :--- | :--- |
| 1 | **North America** | `$8,350.00` | `$1,970.00` |
| 2 | **Europe** | `$4,820.00` | `$1,160.00` |
| 3 | **Asia Pacific** | `$3,180.00` | `$915.00` |
| 4 | **Latin America** | `$2,780.00` | `$640.00` |
| 5 | **Middle East & Africa** | `$1,120.00` | `$210.00` |

### Top 5 Products by Sales
| Rank | Product Name | Category | Total Sales ($) | Total Profit ($) |
| :--- | :--- | :--- | :--- | :--- |
| 1 | **MacBook Pro 16** | Technology | `$3,200.00` | `$780.00` |
| 2 | **ThinkPad X1 Carbon** | Technology | `$2,950.00` | `$720.00` |
| 3 | **Conference Table Oak** | Furniture | `$2,750.00` | `$580.00` |
| 4 | **iPad Pro 12.9** | Technology | `$2,400.00` | `$610.00` |
| 5 | **Dell UltraSharp 27** | Technology | `$1,800.00` | `$420.00` |

### Top 5 Customers by Sales
| Rank | Customer Name | Total Sales ($) | Total Profit ($) |
| :--- | :--- | :--- | :--- |
| 1 | **Aarav Sharma** | `$5,600.00` | `$1,390.00` |
| 2 | **Liam O'Connor** | `$2,950.00` | `$720.00` |
| 3 | **Mateo Silva** | `$2,780.00` | `$640.00` |
| 4 | **Sophia Miller** | `$2,750.00` | `$580.00` |
| 5 | **Kenji Takahashi** | `$2,540.00` | `$730.00` |

---

## Repository Files
* `README.md` — Dashboard architecture, visual documentation, KPI tables, and Power BI Service publishing steps.
* `DAX_Measures_Week4.dax` — DAX measures for Sales, Profit, Discount KPIs, and Month sorting.
* `theme_branding.json` — Custom Power BI JSON theme file for corporate colors and typography.
* `Global_Superstore_2022.csv` — Global Superstore 2022 dataset with `Order Date`, `Region`, `Segment`, `Category`, `Customer Name`, `Product Name`, `Sales`, `Profit`, `Quantity`, and `Discount`.