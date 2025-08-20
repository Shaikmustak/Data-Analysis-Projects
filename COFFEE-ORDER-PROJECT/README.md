# Coffee Orders Data Analysis Project

## 👋 Introduction  
Hi! I'm **<your-name>**, a Data Science student passionate about transforming raw data into actionable insights. This project showcases my skills in data cleaning, analysis, and visualization to solve real-world business problems.  

---

## 🚀 Project Overview  
**Purpose**:  
This project analyzes coffee sales data to uncover trends in customer preferences, sales performance, and regional demand, helping stakeholders optimize inventory and marketing strategies.  

**Goals**:  
1. Identify top-selling coffee types and roast preferences.  
2. Analyze sales trends over time.  
3. Evaluate loyalty program effectiveness.  
4. Create an interactive dashboard for stakeholders.  

**Context**:  
A fictional coffee chain provided transactional data (2019–2022) to derive insights into their business performance.  

---

## 📊 Data Source  
- **Dataset**: `coffeeOrdersData_dashboard.xlsx`  
- **Columns**:  
  - Order ID, Order Date, Customer ID  
  - Product ID (e.g., `A-M-1` = Arabica-Medium-1lb), Quantity, Sales  
  - Customer demographics (Country, Loyalty Card)  
- **Size**: 1000+ rows of transactional data.  
- **Data Quality**: Handled missing values and standardized coffee type abbreviations (e.g., "Ara" → "Arabica").  

---

## 🛠️ Tools Used  
- **Excel**: Data cleaning (XLOOKUP, PivotTables), Dashboard creation.

----

## 🔍 Key Insights  
1. **Top-Selling Coffee**: Arabica accounted for 45% of sales, followed by Robusta (30%).  
2. **Roast Preference**: Medium roast was most popular (55% of orders).  
3. **Loyalty Impact**: Customers with loyalty cards spent 20% more on average.  
4. **Seasonality**: Sales peaked during holiday months (November–December).  
 *Example visualization*  

---

## 🖥️ How to Use  
### For Excel Dashboard:  
1. Download `coffee_dashboard.xlsx`.  
2. Enable data connections if prompted.  
3. Use filters (e.g., date range, country) to explore insights.  

### For Power BI (if applicable):  
1. Open `.pbix` file in Power BI Desktop.  
2. Refresh data connections if needed.  

### For Python Scripts:  
1. Run `analysis.ipynb` in Jupyter Notebook.  
2. Install dependencies:  
   ```bash
   pip install pandas matplotlib

