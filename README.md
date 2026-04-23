# 🟡 Blinkit Business Dashboard

A complete data analysis and visualization project built using **Tableau**, based on Blinkit's operational data.

---

## 📁 Project Structure

```
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
└── README.md
```

---

##  Data Cleaning

Cleaned **9 datasets** with the following steps:

| Table | Changes Made |
|---|---|
| customers | Name → Title case, Email → lowercase, Date format fixed |
| customer_feedback | Date format fixed, Sentiment standardized |
| delivery_performance | Null values → "Not Delayed" |
| inventory | Date fixed, Added `usable_stock`, `damage_pct` |
| inventoryNew | **7,359 duplicates removed**, Added `usable_stock`, `damage_pct` |
| marketing_performance | Date fixed, Added `ctr`, `conversion_rate` |
| order_items | Added `total_price` column |
| orders | Date & time fixed, Status standardized |
| products | Name/Brand → Title case, Added `discount_pct` |

---

##  Dashboard Features

Built using **Tableau Desktop** with Blinkit brand colors.

### KPI Cards
- Total Orders — **5,000**
- Total Revenue — **₹1,10,09,309**
- Avg. Order Value — **₹1,102**
- Total Products — **268**

### Charts
- 📈 Monthly Revenue Trend (Line Chart)
- 🏆 Top 10 Products by Revenue (Bar Chart)
- 🍩 Customer Segment Breakdown (Donut Chart)
- 🚚 Delivery Status (Donut Chart)
- 😊 Sentiment Analysis (Bar Chart)
- 💳 Payment Method Analysis (Bar Chart)
- ⭐ Rating Distribution (Bar Chart)

---

## 🛠️ Tools Used

- **Tableau Desktop** — Dashboard & Visualization

---

## 👤 Author

Made with ❤️ as part of Data Analytics Bootcamp
