
# Sales Performance Dashboard

### 📊 Dashboard Link: [Insert your published Power BI link here]

---

## 🧩 Problem Statement

The **Sales Performance Dashboard** helps businesses monitor and evaluate their overall sales and profit performance. This dashboard provides insights into:

- Total revenue and profit
- Performance by state and product category
- Monthly and yearly sales trends
- Profitability by product category
- Customer- and product-level transaction analysis

It empowers decision-makers to take data-driven actions for boosting sales and improving underperforming areas.

---

## 🛠️ Steps Followed

1. **Data Import**: Loaded sales data into Power BI Desktop.
2. **Data Cleaning**:
   - Removed nulls and duplicates
   - Corrected data types
   - Extracted `Year`, `Month`, and `Quarter` from the date column
3. **Measure Creation (DAX)**:
   ```DAX
   Total Sales = SUM(Sales[Revenue])
   Total Profit = SUM(Sales[Profit])
   ```
4. **KPI Cards**:
   - Displayed `Total Sales` and `Total Profit` using card visuals
5. **Visualizations**:
   - **Bar Chart**: Total Sales by State and Category
   - **Line Chart**: Sales Trends by Month and Year
   - **Stacked Column Chart**: Sales by Quantity and Category
   - **Pie Chart**: Profit Distribution by Category
   - **Table**: Customer-level sales and product information
6. **Slicers**:
   - Year
   - Quarter
7. **Styling**:
   - Applied a clean layout with a professional black-and-white theme
   - Added headers, section titles, and slicers for interactivity
8. **Publish**: Report was deployed to Power BI Service for business use.

---

## 📈 Insights from the Dashboard

### 🔹 KPI Highlights

- **Total Sales**: `$2.30M`
- **Total Profit**: `$286.4K`

---

### 🔹 Top Performing States

- **California**
- **New York**
- **Texas**
- **Washington**

These states lead in total sales.

---

### 🔹 Profit by Category

| Category        | Profit     | % Contribution |
|----------------|------------|----------------|
| Furniture       | $145K      | 50.7%          |
| Office Supplies | $122K      | 42.7%          |
| Technology      | $18.4K     | 6.4%           |

> Furniture brings the highest profit, while Technology has the lowest.

---

### 🔹 Monthly Sales Trend

- Sales peak in **December**
- Lower sales in **February**
- Steady growth observed from **Q2 onwards**

---

### 🔹 Sales by Quantity

- Sales spike between quantity levels **3 to 6**
- Most sales volume seen in **Furniture** and **Office Supplies**

---

### 🔹 Customer-Product Mapping

- Table helps identify top products and regions per customer
- Supports personalized marketing and sales recommendations

---

## 📸 Dashboard Snapshot

![Sales Dashboard](./Screenshot%202025-05-25%20151605.png)

---

## ✅ Conclusion

This interactive dashboard serves as a powerful tool for sales strategy and reporting. By monitoring KPIs, identifying top regions and products, and drilling down to customer transactions, businesses can drive efficiency and growth.

> Made with ❤️ in Power BI.

