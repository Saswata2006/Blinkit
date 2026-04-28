<div align="center">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" alt="Tableau" />
  <img src="https://img.shields.io/badge/Data_Analysis-FFCA28?style=for-the-badge&logo=googleanalytics&logoColor=black" alt="Data Analysis" />
  
  <h1>🟡 Blinkit Business Dashboard</h1>
  <p><strong>A complete data analysis and visualization project built using Tableau, based on Blinkit's operational data.</strong></p>
</div>

---

## 📖 Table of Contents
- [About the Project](#-about-the-project)
- [Key Features & Insights](#-key-features--insights)
- [Project Structure](#-project-structure)
- [Data Cleaning Process](#-data-cleaning-process)
- [Tech Stack](#-tech-stack)

---

## 🎯 About the Project

This project focuses on providing deep insights into Blinkit's operations through an interactive and comprehensive dashboard. By analyzing massive amounts of data ranging from customer feedback to delivery performance and inventory management, this dashboard acts as a single point of truth for business intelligence.

The primary goal is to visualize critical business metrics, enabling stakeholders to make data-driven decisions swiftly and effectively.

---

## 📊 Key Features & Insights

The dashboard is built using **Tableau Desktop**, fully customized with Blinkit's brand guidelines to maintain consistency and professionalism.

### 📈 Executive KPIs
- **Total Orders**: 5,000
- **Total Revenue**: ₹1,10,09,309
- **Avg. Order Value**: ₹1,102
- **Total Products**: 268

### 📉 Visual Analytics
- **Monthly Revenue Trend**: Line chart showcasing the growth trajectory over time.
- **Top 10 Products by Revenue**: Bar chart highlighting the best-performing items.
- **Customer Segment Breakdown**: Donut chart detailing target demographics.
- **Delivery Status**: Donut chart tracking delivery efficiency and delays.
- **Sentiment Analysis**: Bar chart measuring customer satisfaction levels.
- **Payment Method Analysis**: Bar chart illustrating user payment preferences.
- **Rating Distribution**: Bar chart displaying overall product and service ratings.

---

## 📁 Project Structure

The repository is organized logically to separate raw/cleaned data from documentation.

```text
blinkit-dashboard/
├── cleaned_data/
│   ├── blinkit_customers.csv
│   ├── blinkit_customer_feedback.csv
│   ├── blinkit_orders.csv
│   ├── blinkit_order_items.csv
│   ├── blinkit_delivery_performance.csv
│   ├── blinkit_inventory.csv
│   ├── blinkit_inventoryNew.csv
│   ├── blinkit_marketing_performance.csv
│   └── blinkit_products.csv
├── Blinkit Dashboard.pdf
├── Category_Icons.xlsx
├── Rating_Icon.xlsx
└── README.md
```

---

## 🧹 Data Cleaning Process

Extensive data cleaning and preprocessing were performed on **9 distinct datasets** to ensure high-quality visualizations. The transformations are detailed below:

| Table | Major Transformations |
| :--- | :--- |
| **`customers`** | Name to Title case, Email to lowercase, Date format standardization. |
| **`customer_feedback`** | Date format standardization, Sentiment classification standardized. |
| **`delivery_performance`**| Handled null values (Replaced with "Not Delayed"). |
| **`inventory`** | Date formatting fixed, Engineered new metrics (`usable_stock`, `damage_pct`). |
| **`inventoryNew`** | Removed **7,359 duplicate records**, Engineered metrics (`usable_stock`, `damage_pct`). |
| **`marketing_performance`**| Date formatting fixed, Calculated `ctr` (Click-Through Rate) and `conversion_rate`. |
| **`order_items`** | Calculated `total_price` column. |
| **`orders`** | Date and time formats standardized, Order status text normalized. |
| **`products`** | Name and Brand mapped to Title case, Calculated `discount_pct`. |

---

## 🛠 Tech Stack

### Data Visualization & Analytics
<div align="left">
  <img src="https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=Tableau&logoColor=white" alt="Tableau" />
  <img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel" />
</div>

- **Tableau Desktop**: Primary tool for dashboard creation, data modeling, and visualization.
- **Excel/CSV Data**: Underlying data format for structured data cleaning and processing.
