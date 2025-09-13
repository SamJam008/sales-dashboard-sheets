#  Sales Dashboard – Google Sheets

This project demonstrates **data visualization and anomaly detection** skills using Google Sheets.  
I used a Dunder-Mufflin Paper Company dataset (~1K+ records) with the following fields:  
`Product, Category, Region, Date, Revenue, Profit`.

---

##  Features
- **Pivot Tables** for multi-dimensional analysis:
  - Revenue & Profit by Region
  - Top Products by Sales
  - Category & Time-based trends
- **Interactive Slicers** to filter by Region, Category, and Time
- **Charts & Visuals**:
  - Line chart: Revenue trends over time
  - Bar chart: Top products by sales
  - Column chart: Profit by region
- **Anomaly Detection**:
  - Conditional formatting to flag **negative profits**
  - Highlight **seasonal spikes** and outliers

---

##  Dashboard Preview

### Full Dashboard
![Dashboard Overview](./images/dashboard_overview.png)

### Slicer Example
![Filtered by Region](./images/slicer_example.png)

### Anomaly Highlight
![Negative Profit Highlight](./images/anomaly_example.png)

---

##  Key Insights
- **Regional Profit Leakage:** South region shows frequent negative profits despite strong sales.  
- **Seasonal Spikes:** Q4 consistently outperforms other quarters, driven by Electronics.  
- **Product Trends:** Chairs & Phones together drive ~40% of revenue but have volatile margins.  

---

##  Deliverables
- [ Live Dashboard (Google Sheets)](INSERT_YOUR_LINK_HERE)  
- [ Dataset (CSV)](./data/sales_dataset.csv)  
- [ README (this file)](./README.md)  

---

## 🛠 How to Reproduce
1. Download dataset (`CSV` provided in repo).  
2. Import into **Google Sheets**.  
3. Build pivot tables → add slicers → insert charts.  
4. Apply conditional formatting for anomalies (negative profit, outliers).  
5. Arrange visuals in a clean **Dashboard sheet**.  

---

##  Resume Line
> **“Developed an interactive sales dashboard on 1K+ records in Google Sheets, leveraging pivot tables, slicers, and anomaly flags to uncover regional profit leakage and seasonal demand spikes.”**
