# 🛍️ Customer Purchase Behaviour & Sentiment Analysis

This repository hosts a comprehensive end-to-end data analytics project that analyzes **customer purchase behaviour** and **sentiment** using **MySQL**, **Python**, and **Power BI**. It combines structured transactional data with customer reviews to deliver actionable insights, supporting business decisions in marketing, product strategy, and customer experience.

---

## 🎯 Project Overview

### 📌 Objective

To identify patterns in customer purchase behaviour and uncover customer sentiment through reviews, enabling data-driven decisions for product development, marketing strategies, and customer engagement.

---

<div align="center">
  <img src="https://github.com/pruthvirajshitole/Ecom-Insights-Hub/blob/main/Ecom%20Insights%20Hub.gif" height="300" alt="Ecom Insights Dashboard Demo" />
</div>

---

## 📊 Datasets

### 1. **Customer Purchase Data** (`customer_purchase_data.csv`)

Fields:

* `TransactionID`
* `CustomerID`
* `CustomerName`
* `ProductID`
* `ProductName`
* `ProductCategory`
* `PurchaseQuantity`
* `PurchasePrice`
* `PurchaseDate`
* `Country`

### 2. **Customer Reviews Data** (`customer_reviews_data.csv`)

Fields:

* `ReviewID`
* `CustomerID`
* `ProductID`
* `ReviewText`
* `ReviewDate`

---

## 🔧 Project Components

### 1. 🗃️ Data Engineering (MySQL)

* Created a normalized MySQL database schema
* Imported and cleaned raw data
* Built relational joins for product, customer, and review analytics
* Queried:

  * Total revenue and purchases by customer/product
  * Monthly/quarterly purchase trends
  * Category-wise performance metrics

### 2. 🐍 Data Analysis (Python)

* Connected to MySQL using `pymysql`
* Cleaned and structured data using `pandas`
* Performed **sentiment analysis** with `TextBlob`
* Labeled reviews as **Positive**, **Neutral**, or **Negative**
* Visualized:

  * Top customers & categories
  * Revenue breakdown
  * Sentiment distributions using `matplotlib` & `seaborn`

### 3. 📊 Business Intelligence (Power BI)

* Developed an **interactive Power BI dashboard** featuring:

  * Revenue and order trends
  * Top-performing categories & customers
  * Country-wise and category-wise sentiment heatmaps
* Enabled slicers for:

  * Date ranges
  * Product categories
  * Customer segments

---

## 🚀 Project Deliverables

| Component          | File                             |
| ------------------ | -------------------------------- |
| MySQL Script       | `Ecom Insights Hub_MySQL.sql`    |
| Python Notebook    | `Ecom Insights Hub_Python.ipynb` |
| Power BI Dashboard | `Ecom Insights Hub_PowerBI.pbix` |
| PDF Summary        | `Ecom Insights Hub.pdf`          |

---

## 🧰 Tools and Technologies

| Tool                                                                                                           | Purpose                             |
| -------------------------------------------------------------------------------------------------------------- | ----------------------------------- |
| ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge\&logo=mysql\&logoColor=white)           | Relational data storage and queries |
| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)        | Data analysis and scripting         |
| ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge\&logo=powerbi\&logoColor=black) | Dashboarding and reporting          |
| ![TextBlob](https://img.shields.io/badge/TextBlob-Text--Analysis-green?style=for-the-badge)                    | Sentiment analysis                  |

---

## 🛠️ How to Use

### 🔗 Prerequisites

* MySQL installed and running
* Python 3.x with required libraries (`pandas`, `numpy`, `TextBlob`, `matplotlib`, `seaborn`, `pymysql`)
* Power BI Desktop installed

### 🚦 Steps to Run

```bash
# Step 1: Clone the repository
https://github.com/pruthvirajshitole/Ecom-Insights-Hub.git

# Step 2: Set up the MySQL database
Run `Ecom Insights Hub_MySQL.sql` to create tables and load data

# Step 3: Run the Python notebook
Execute `Ecom Insights Hub_Python.ipynb` for analysis and sentiment scoring

# Step 4: Launch the dashboard
Open `Ecom Insights Hub_PowerBI.pbix` in Power BI Desktop
```

---

## 📈 Results and Insights

* 📦 **Top Products & Categories** by revenue and purchase frequency
* 🧾 **Purchase Trends** across months and quarters
* 🌍 **Country-wise** customer activity and revenue
* 🙂 **Sentiment Breakdown** per product & category
* 👥 **High-Value Customers** identified by spend & frequency

---

## 📁 Repository Structure

```
├── data/
│   ├── customer_purchase_data.csv         # Raw transaction data
│   ├── customer_reviews_data.csv          # Raw review data
│   ├── cleaned_reviews_data.csv           # Reviews with sentiment
├── sql/
│   └── Ecom Insights Hub_MySQL.sql        # Database schema & queries
├── notebooks/
│   └── Ecom Insights Hub_Python.ipynb     # Data analysis & sentiment
├── dashboard/
│   ├── Ecom Insights Hub_PowerBI.pbix     # Power BI interactive report
│   └── Ecom Insights Hub.pdf              # Dashboard in PDF format
├── README.md                              # Project documentation

```

## 📄 License

This project is licensed for **educational and non-commercial use only**.  
If you use or adapt this repository, please provide appropriate credit by citing the source.

---

## ⚠️ Disclaimer

This project uses **synthetic datasets** created solely for educational and demonstration purposes.  
The data does **not** represent any real-world or proprietary source.

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

---
<div align="center">
Made with ❤️ for a Ecommerce Providers
</div>

