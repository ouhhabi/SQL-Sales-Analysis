Sales Data Analysis Dashboard (MySQL + Power BI)

## 📌 Project Overview

This project analyzes sales data using **MySQL** and visualizes insights through an **interactive Power BI dashboard**.

The goal is to transform raw sales data into clear business insights such as revenue trends, customer metrics, and regional performance.

---

## 🛠 Tools Used

- **MySQL** – Data storage and SQL analysis  
- **Power BI** – Interactive dashboard  
- **DAX** – Business metrics calculations  
- **GitHub** – Version control

---

## 📂 Dataset

The dataset contains sales information with the following fields:

- `date`
- `region`
- `client_id`
- `type_dossier`
- `CA` (Revenue)

---

## 📊 Dashboard Features

### 🔹 Global KPIs
- Total Revenue
- Number of Clients
- Average Revenue per Client

DAX measures used:

DAX
CA total = SUM(ventes[CA])

Nombre de clients = DISTINCTCOUNT(ventes[client_id])

CA moyen par client = DIVIDE([CA total], [Nombre de clients])
🔹 Time Analysis

Line chart showing revenue evolution over time with a date filter.

🔹 Regional Analysis

Map visualization showing revenue by region.

🔹 Case Type Analysis

Treemap → Revenue by type of case

Stacked bar chart → Revenue by region and case type

🚀 How to Use

Import the dataset into MySQL.

Connect Power BI to the database.

Open the Power BI dashboard (.pbix) to explore the insights.

👨‍💻 Author

Data analysis project built to practice SQL, Power BI, and DAX for business intelligence and data visualization.
