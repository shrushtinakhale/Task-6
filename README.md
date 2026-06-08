# 🛒 Online Sales Data — Project README

## 📌 Project Overview

This dataset contains transactional e-commerce sales records spanning **January 1, 2024 to February 13, 2024**. It covers **44 transactions** across 6 product categories, 3 global regions, and 3 payment methods. The data is suitable for sales analysis, revenue reporting, and business intelligence queries.

---

## 📁 Files Included

| File Name                  | Format | Description                         |
|---------------------------|--------|-------------------------------------|
| `Online_Sales_Data.csv`   | CSV    | Raw sales transaction data          |
| `Online_Sales_Data-1.xlsx`| XLSX   | Same dataset in Excel format        |

---

## 🗂️ Dataset Schema

| Column Name       | Data Type | Description                                      |
|------------------|-----------|--------------------------------------------------|
| Transaction ID   | Integer   | Unique identifier for each transaction           |
| Date             | String    | Date of transaction (DD-MM-YYYY format)          |
| Product Category | String    | Category of the product sold                     |
| Product Name     | String    | Full name of the product                         |
| Units Sold       | Integer   | Number of units sold in the transaction          |
| Unit Price       | Float     | Price per unit in USD                            |
| Total Revenue    | Float     | Total revenue = Units Sold × Unit Price (USD)    |
| Region           | String    | Geographic region of the sale                    |
| Payment Method   | String    | Method used for payment                          |

---

## 📊 Full Dataset

| Transaction ID | Date       | Product Category | Product Name                              | Units Sold | Unit Price | Total Revenue | Region        | Payment Method |
|---------------|------------|-----------------|-------------------------------------------|-----------|-----------|--------------|--------------|---------------|
| 10001         | 01-01-2024 | Electronics      | iPhone 14 Pro                             | 2         | 999.99    | 1999.98      | North America | Credit Card   |
| 10002         | 02-01-2024 | Home Appliances  | Dyson V11 Vacuum                          | 1         | 499.99    | 499.99       | Europe        | PayPal        |
| 10003         | 03-01-2024 | Clothing         | Levi's 501 Jeans                          | 3         | 69.99     | 209.97       | Asia          | Debit Card    |
| 10004         | 04-01-2024 | Books            | The Da Vinci Code                         | 4         | 15.99     | 63.96        | North America | Credit Card   |
| 10005         | 05-01-2024 | Beauty Products  | Neutrogena Skincare Set                   | 1         | 89.99     | 89.99        | Europe        | PayPal        |
| 10006         | 06-01-2024 | Sports           | Wilson Evolution Basketball               | 5         | 29.99     | 149.95       | Asia          | Credit Card   |
| 10007         | 07-01-2024 | Electronics      | MacBook Pro 16-inch                       | 1         | 2499.99   | 2499.99      | North America | Credit Card   |
| 10008         | 08-01-2024 | Home Appliances  | Blueair Classic 480i                      | 2         | 599.99    | 1199.98      | Europe        | PayPal        |
| 10009         | 09-01-2024 | Clothing         | Nike Air Force 1                          | 6         | 89.99     | 539.94       | Asia          | Debit Card    |
| 10010         | 10-01-2024 | Books            | Dune by Frank Herbert                     | 2         | 25.99     | 51.98        | North America | Credit Card   |
| 10011         | 11-01-2024 | Beauty Products  | Chanel No. 5 Perfume                      | 1         | 129.99    | 129.99       | Europe        | PayPal        |
| 10012         | 12-01-2024 | Sports           | Babolat Pure Drive Tennis Racket          | 3         | 199.99    | 599.97       | Asia          | Credit Card   |
| 10013         | 13-01-2024 | Electronics      | Samsung Galaxy Tab S8                     | 2         | 749.99    | 1499.98      | North America | Credit Card   |
| 10014         | 14-01-2024 | Home Appliances  | Keurig K-Elite Coffee Maker               | 1         | 189.99    | 189.99       | Europe        | PayPal        |
| 10015         | 15-01-2024 | Clothing         | North Face Down Jacket                    | 2         | 249.99    | 499.98       | Asia          | Debit Card    |
| 10016         | 16-01-2024 | Books            | Salt, Fat, Acid, Heat by Samin Nosrat     | 3         | 35.99     | 107.97       | North America | Credit Card   |
| 10017         | 17-01-2024 | Beauty Products  | Dyson Supersonic Hair Dryer               | 1         | 399.99    | 399.99       | Europe        | PayPal        |
| 10018         | 18-01-2024 | Sports           | Manduka PRO Yoga Mat                      | 4         | 119.99    | 479.96       | Asia          | Credit Card   |
| 10019         | 19-01-2024 | Electronics      | Garmin Forerunner 945                     | 2         | 499.99    | 999.98       | North America | Credit Card   |
| 10020         | 20-01-2024 | Home Appliances  | Ninja Professional Blender                | 1         | 99.99     | 99.99        | Europe        | PayPal        |
| 10021         | 21-01-2024 | Clothing         | Zara Summer Dress                         | 3         | 59.99     | 179.97       | Asia          | Debit Card    |
| 10022         | 22-01-2024 | Books            | Gone Girl by Gillian Flynn                | 2         | 22.99     | 45.98        | North America | Credit Card   |
| 10023         | 23-01-2024 | Beauty Products  | Olay Regenerist Face Cream                | 1         | 49.99     | 49.99        | Europe        | PayPal        |
| 10024         | 24-01-2024 | Sports           | Adidas FIFA World Cup Football            | 3         | 29.99     | 89.97        | Asia          | Credit Card   |
| 10025         | 25-01-2024 | Electronics      | Bose QuietComfort 35 Headphones           | 1         | 299.99    | 299.99       | North America | Credit Card   |
| 10026         | 26-01-2024 | Home Appliances  | Panasonic NN-SN966S Microwave             | 1         | 179.99    | 179.99       | Europe        | PayPal        |
| 10027         | 27-01-2024 | Clothing         | Adidas Ultraboost Shoes                   | 2         | 179.99    | 359.98       | Asia          | Debit Card    |
| 10028         | 28-01-2024 | Books            | Pride and Prejudice by Jane Austen        | 3         | 12.99     | 38.97        | North America | Credit Card   |
| 10029         | 29-01-2024 | Beauty Products  | MAC Ruby Woo Lipstick                     | 1         | 29.99     | 29.99        | Europe        | PayPal        |
| 10030         | 30-01-2024 | Sports           | Nike Air Zoom Pegasus 37                  | 2         | 129.99    | 259.98       | Asia          | Credit Card   |
| 10031         | 31-01-2024 | Electronics      | Sony WH-1000XM4 Headphones               | 2         | 349.99    | 699.98       | North America | Credit Card   |
| 10032         | 01-02-2024 | Home Appliances  | Instant Pot Duo                           | 3         | 89.99     | 269.97       | Europe        | PayPal        |
| 10033         | 02-02-2024 | Clothing         | Under Armour HeatGear T-Shirt             | 5         | 29.99     | 149.95       | Asia          | Debit Card    |
| 10034         | 03-02-2024 | Books            | 1984 by George Orwell                     | 4         | 19.99     | 79.96        | North America | Credit Card   |
| 10035         | 04-02-2024 | Beauty Products  | L'Oreal Revitalift Serum                  | 2         | 39.99     | 79.98        | Europe        | PayPal        |
| 10036         | 05-02-2024 | Sports           | Peloton Bike                              | 1         | 1895.00   | 1895.00      | Asia          | Credit Card   |
| 10037         | 06-02-2024 | Electronics      | Apple Watch Series 8                      | 3         | 399.99    | 1199.97      | North America | Credit Card   |
| 10038         | 07-02-2024 | Home Appliances  | Roomba i7+                                | 2         | 799.99    | 1599.98      | Europe        | PayPal        |
| 10039         | 08-02-2024 | Clothing         | Columbia Fleece Jacket                    | 4         | 59.99     | 239.96       | Asia          | Debit Card    |
| 10040         | 09-02-2024 | Books            | Harry Potter and the Sorcerer's Stone     | 3         | 24.99     | 74.97        | North America | Credit Card   |
| 10041         | 10-02-2024 | Beauty Products  | Estee Lauder Advanced Night Repair        | 1         | 105.00    | 105.00       | Europe        | PayPal        |
| 10042         | 11-02-2024 | Sports           | Fitbit Charge 5                           | 2         | 129.99    | 259.98       | Asia          | Credit Card   |
| 10043         | 12-02-2024 | Electronics      | GoPro HERO10 Black                        | 3         | 399.99    | 1199.97      | North America | Credit Card   |
| 10044         | 13-02-2024 | Home Appliances  | Nespresso VertuoPlus                      | 1         | 199.99    | 199.99       | Europe        | PayPal        |

---

## 🔍 Analytical Queries & Results

### Query 1 — Total Revenue by Product Category

> Which product category generates the most revenue?

```sql
SELECT product_category,
       SUM(total_revenue) AS total_revenue
FROM online_sales
GROUP BY product_category
ORDER BY total_revenue DESC;
```

**Result:**

| Product Category | Total Revenue (USD) |
|-----------------|-------------------|
| Electronics      | $10,399.84         |
| Home Appliances  | $4,239.88          |
| Sports           | $3,734.81          |
| Clothing         | $2,179.75          |
| Beauty Products  | $884.93            |
| Books            | $463.79            |

> **Insight:** Electronics dominates revenue at 47% of total sales, driven by high unit prices (MacBook Pro, iPhone, Samsung Tab).

---

### Query 2 — Total Revenue by Region

> Which geographic region contributes the most to overall sales?

```sql
SELECT region,
       SUM(total_revenue) AS total_revenue
FROM online_sales
GROUP BY region
ORDER BY total_revenue DESC;
```

**Result:**

| Region        | Total Revenue (USD) |
|--------------|-------------------|
| North America | $10,863.63         |
| Asia          | $5,914.56          |
| Europe        | $5,124.81          |

> **Insight:** North America leads with ~49% of total revenue. Asia and Europe are relatively balanced at ~27% and ~23% respectively.

---

### Query 3 — Top 5 Products by Units Sold

> Which products are the most popular by volume?

```sql
SELECT product_name,
       SUM(units_sold) AS total_units_sold
FROM online_sales
GROUP BY product_name
ORDER BY total_units_sold DESC
LIMIT 5;
```

**Result:**

| Product Name                   | Units Sold |
|-------------------------------|-----------|
| Nike Air Force 1               | 6         |
| Under Armour HeatGear T-Shirt  | 5         |
| Wilson Evolution Basketball    | 5         |
| 1984 by George Orwell          | 4         |
| Manduka PRO Yoga Mat           | 4         |

> **Insight:** Budget-to-mid-range items dominate volume sales. Low-price products like clothing, books, and sports gear sell more units despite lower individual revenue contribution.

---

### Query 4 — Revenue & Transactions by Payment Method

> How do customers prefer to pay, and which method drives the most revenue?

```sql
SELECT payment_method,
       SUM(total_revenue)   AS total_revenue,
       COUNT(transaction_id) AS transaction_count
FROM online_sales
GROUP BY payment_method
ORDER BY total_revenue DESC;
```

**Result:**

| Payment Method | Total Revenue (USD) | Transaction Count |
|---------------|-------------------|------------------|
| Credit Card    | $14,598.44         | 22               |
| PayPal         | $5,124.81          | 15               |
| Debit Card     | $2,179.75          | 7                |

> **Insight:** Credit Card is the dominant payment method, accounting for 66% of total revenue and 50% of all transactions. PayPal is the second choice, popular in the Europe region.

---

### Query 5 — Top 5 Highest Revenue Days

> Which individual days produced the highest single-day revenue?

```sql
SELECT date,
       SUM(total_revenue) AS daily_revenue
FROM online_sales
GROUP BY date
ORDER BY daily_revenue DESC
LIMIT 5;
```

**Result:**

| Date       | Daily Revenue (USD) |
|-----------|-------------------|
| 07-01-2024 | $2,499.99          |
| 01-01-2024 | $1,999.98          |
| 05-02-2024 | $1,895.00          |
| 07-02-2024 | $1,599.98          |
| 13-01-2024 | $1,499.98          |

> **Insight:** The highest revenue days are driven by single high-ticket Electronics purchases (MacBook Pro on Jan 7, iPhone 14 Pro on Jan 1). The Peloton Bike sale on Feb 5 is the only Sports item to break the top 5.

---

## 📈 Summary Statistics

| Metric                    | Value         |
|--------------------------|--------------|
| Total Transactions        | 44            |
| Date Range                | 01-01-2024 → 13-02-2024 |
| Total Revenue             | $21,903.00    |
| Average Revenue / Transaction | $497.80   |
| Max Single Transaction    | $2,499.99     |
| Min Single Transaction    | $29.99        |
| Average Units Per Transaction | 2.32      |
| Unique Products           | 44            |
| Product Categories        | 6             |
| Regions                   | 3             |
| Payment Methods           | 3             |

---

## 🔑 Key Dimensions

| Dimension         | Values                                                              |
|------------------|---------------------------------------------------------------------|
| Product Category | Electronics, Home Appliances, Sports, Clothing, Beauty Products, Books |
| Region           | North America, Asia, Europe                                         |
| Payment Method   | Credit Card, PayPal, Debit Card                                     |

---

*Dataset covers January–February 2024. All revenue values are in USD.*
