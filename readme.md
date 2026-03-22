# 🛒 Blinkit Sales Performance Dashboard (Power BI)

An **interactive and visually rich Power BI dashboard** built to analyze Blinkit’s sales performance across products, outlets, and customer behavior.

This dashboard transforms raw data into **actionable insights**, helping stakeholders make faster and smarter business decisions.

---

## 🎯 Project Objective

- 📊 Track overall sales performance  
- 🛍️ Analyze product category contribution  
- 🏪 Evaluate outlet performance by size & location  
- ⭐ Understand customer satisfaction trends  

---

## 📊 Key Performance Indicators (KPIs)

- 💰 **Total Sales:** $1.20M → Overall revenue generated  
- 📈 **Average Sales:** $141 → Avg revenue per transaction  
- 📦 **Number of Items Sold:** 8.5K → Total product volume  
- ⭐ **Average Rating:** 3.9 → Customer satisfaction score  

---

## 📷 Dashboard Preview

![Dashboard Overview](images/dashboard_overview.png)

---

## 🎛️ Interactive Slicers (Filters)

The dashboard includes dynamic slicers that allow users to explore data interactively:

- 📅 **Year** → Analyze trends over time  
- 📍 **Outlet Location** → Compare Tier 1, Tier 2, Tier 3 cities  
- 🏪 **Outlet Size** → Evaluate Small, Medium, High outlets  
- 🛍️ **Item Type** → Drill down into product categories  

💡 These slicers dynamically update **all visuals**, enabling deep analysis.

---

## 📊 Dashboard Insights (Visual Explanation)

### 🍩 Sales Distribution (Donut Charts)
- Shows how **Low Fat vs Regular products** contribute to sales  
- Highlights which **outlet sizes dominate revenue**  

👉 Helps identify **customer preferences and product demand**

---

### 📊 Product Performance (Bar Chart)
- Displays **sales by item type**  
- Clearly highlights top-performing categories like Fruits, Snacks, etc.

👉 Helps in **inventory planning and product focus**

---

### 📈 Sales Trend Over Time (Line Chart)
- Shows how sales vary by **outlet establishment year**  
- Identifies growth patterns and high-performing periods  

👉 Useful for **long-term business strategy**

---

### 📍 Location-Based Performance
- Compares sales across **Tier 1, Tier 2, Tier 3 cities**  

👉 Helps understand **regional demand and expansion opportunities**

---

### 📋 Outlet Performance (Matrix Table)
- Combines multiple KPIs:
  - Total Sales  
  - Avg Sales  
  - Number of Items  
  - Rating  
  - Item Visibility  

👉 Provides a **complete performance snapshot of each outlet type**

---

## 🧠 Data Model

This project is built using a **Star Schema Model**:

- **Fact Table:** Sales transactions  
- **Dimension Tables:** Item, Outlet, Date  

This ensures:
- Faster performance ⚡  
- Better filtering 🔍  
- Scalable design 📈  

![Data Model](images/data_model.png)

---

## 🛠️ Tools & Technologies

- Power BI  
- DAX (Data Analysis Expressions)  
- Excel  
- Data Modeling  

---

## 📈 Key Insights

- 📍 Tier 3 outlets generate the highest revenue  
- 🥛 Low-fat products are highly preferred  
- 🏪 Medium-sized outlets perform best  
- ⭐ Customer ratings are consistent (~3.9)  
- 📅 Older outlets contribute significantly to sales  

---

## 🚀 Business Impact

- Enables real-time sales monitoring  
- Helps identify high-performing products  
- Supports better inventory and marketing decisions  
- Improves strategic planning  

---

## 📂 Project Structure
```
Blinkit-Dashboard/
│
├── Data/
│     └── blinkit_dataset.xlsx
│
├── PowerBI/
│     └── blinkit_dashboard.pbix
│
├── images/
│     ├── dashboard_overview.png
│     ├── data_model.png
│
└── README.md
```
---

## 👨‍💻 Author

**Diwakar Kumar**  
Aspiring Data Analyst | Power BI Enthusiast  

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐  