# 🛒 Retail Business Analytics Report - Power BI

An end-to-end interactive Power BI dashboard analyzing retail sales, profit & customer demographics using sales table.

### 📊 Dashboard Preview

**1. Sales Dashboard**
![Sales Dashboard](./sales.png)
KPIs: Total Sales $12.64M | Sales LY $8.34M | YoY 51.54% | Avg per Order $504.99

**2. Profit Dashboard**
![Profit Dashboard](./profit.png)
KPIs: Total Profit $1.47M | Profit LY $963.29K | YoY 52.34% | Avg per Order $58.62

**3. Demographics Dashboard**
![Demographics Dashboard](./demographics.png)
KPIs: 1590 Customers | 25K Orders | 3797 Products | Avg Sales/State $11.56K

### 🗃️ Dataset
- File: `global_retail_sales_data.xlsx`
- Table Used: `sales table`
- Contains Sales, Profit, Customer, Product, Category, Segment, Region data

### 🛠️ Tools & Features
- Power BI Desktop, Power Query, DAX
- Page Navigation (SALES | PROFIT | DEMOGRAPHICS)
- What-If Parameter for Dynamic Top N
- Dynamic Title DAX: `title_state = "TOP " & SELECTEDVALUE(rank_[rank_Value]) & " PROFITABLE STATE"`

### 🔍 Key Insights
- Technology: $4.74M top category
- Consumer: 51.48% of total sales
- US: Top country with $2.3M+ sales
- 51%+ YoY growth in Sales & Profit

### 📂 Files
- `sales.png, profit.png, demographics.png` - Dashboard screenshots
- `global_retail_sales_data.xlsx` - Raw dataset (sales table)

---
**Author:** Aparna Ashyju | GitHub: @aparnaashyju
