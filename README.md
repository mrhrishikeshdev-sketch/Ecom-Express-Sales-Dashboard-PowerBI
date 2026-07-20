# 📊 Ecom Express Sales Dashboard | Power BI

![Dashboard Preview](Images/Dashboard.png)

## 📌 Overview

The **Ecom Express Sales Dashboard** is an interactive Business Intelligence project developed using **Microsoft Power BI**. It helps analyze sales performance, customer purchasing behavior, product performance, regional sales, and order cancellations through interactive dashboards and KPIs.

---

## 🎯 Project Objectives

- Analyze overall sales performance
- Monitor Revenue and Total Orders
- Track Average Order Value (AOV)
- Measure Cancellation Rate
- Identify Lost Revenue due to cancelled orders
- Compare State-wise Revenue
- Analyze Product-wise Revenue
- Study Monthly Revenue Trends

---

# 📈 Key Performance Indicators

| KPI | Value |
|------|-------|
| 💰 Revenue | ₹1.25 Billion |
| 📦 Total Orders | 15.69K |
| 💳 Average Order Value | ₹112.85K |
| ❌ Cancellation Rate | 29.72% |
| 📉 Lost Revenue | ₹525.42 Million |

---

# 📊 Dashboard Features

- Revenue KPI Card
- Average Order Value
- Total Orders
- Cancellation Rate
- Lost Revenue Analysis
- Revenue by Product Name
- Revenue by Category
- Revenue by State
- Monthly Revenue Trend
- Product Category Slicer
- Purchase Date Filter

---

# 🏗 Data Model

The dashboard follows a **Star Schema**.

```
Customer (1)
        |
        |
Orders (*)
        |
        |
Product (1)
```

---

# 📂 Dataset

The project contains three datasets.

### Customer

- CustomerID
- Full Name
- Phone
- City
- State
- Phone Brand
- Operating System

### Orders

- OrderID
- CustomerID
- ProductID
- Quantity
- Purchase Date
- Delivery Time
- Delivery Status

### Product

- ProductID
- Product Name
- Category
- Price
- Rating

---

# 📷 Dashboard Preview

![Dashboard](Images/Dashboard.png)

---

# 📈 Business Insights

- Laptop category generated the highest revenue.
- Maharashtra generated the highest revenue.
- MacBook Air is the highest revenue-generating product.
- Cancellation Rate is **29.72%**.
- Lost Revenue exceeded **₹525 Million**.
- Revenue peaked around **July 2024**.

---

# 🛠 Technologies Used

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling
- CSV
- Business Intelligence

---

# 💡 Skills Demonstrated

- Data Cleaning
- Data Modeling
- Power Query
- DAX
- KPI Design
- Dashboard Design
- Data Visualization
- Business Intelligence

---

# 📁 Repository Structure

```
Dashboard/
Dataset/
Documentation/
Images/
Presentation/
README.md
LICENSE
```

---

# 🚀 How to Use

1. Clone this repository.
2. Open the `.pbix` file using Power BI Desktop.
3. Refresh the datasets if required.
4. Explore the interactive dashboard.

---

# 📌 Future Enhancements

- Sales Forecasting
- Customer Segmentation
- Profit Analysis
- Regional Heat Maps
- Dynamic Tooltips
- Drill-through Reports

---

# 👨‍💻 Author

**Hrishikesh Kshirsagar**

- 🎓 B.E. in Artificial Intelligence & Data Science
- 💼 Aspiring Data Analyst | Power BI Developer
- 🛠 Skills: Power BI, SQL, Python, Machine Learning

---

⭐ If you found this project useful, consider giving it a **Star**.
