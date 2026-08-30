# decodelabs_EDA
# 📊 DecodeLabs Project 2 – Exploratory Data Analysis

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on an e-commerce order dataset using Microsoft Excel.

The analysis explores customer purchasing behavior, product performance, pricing, payment methods, order status, monthly sales trends, coupon usage, referral sources, correlations, and potential outliers.

This project was completed as part of **DecodeLabs Project 2**.

---

## 🎯 Objectives

The main objectives of this project are:

* Clean and organize the dataset
* Understand the structure of the data
* Calculate descriptive statistics
* Analyze customer purchasing patterns
* Examine product-wise order distribution
* Analyze order status
* Identify monthly sales trends
* Study payment methods, coupons, and referral sources
* Identify correlations between numerical variables
* Detect potential outliers
* Generate meaningful business insights

---

## 📂 Dataset

The dataset contains **1,200 e-commerce order records**.

### Important Variables

| Variable        | Description                 |
| --------------- | --------------------------- |
| OrderID         | Unique order identification |
| Date            | Order date                  |
| CustomerID      | Customer identification     |
| Product         | Product purchased           |
| Quantity        | Number of units ordered     |
| UnitPrice       | Price per unit              |
| ShippingAddress | Customer shipping address   |
| PaymentMethod   | Payment method used         |
| ItemsInCart     | Number of items in cart     |
| TotalPrice      | Total value of the order    |

---

## 🛠️ Tools Used

* **Microsoft Excel**
* Data Cleaning
* Descriptive Statistics
* Pivot Tables
* Correlation Analysis
* Data Analysis
* Charts & Visualizations

---

## 🔍 EDA Performed

### 1. Data Cleaning

The dataset was cleaned and organized before performing the analysis.

The cleaned dataset contains **1,200 records** and was used for further statistical and exploratory analysis.

### 2. Descriptive Statistics

Key numerical statistics were calculated for:

* Quantity
* Unit Price
* Items in Cart
* Total Price

| Variable    |    Mean | Median | Maximum | Minimum |
| ----------- | ------: | -----: | ------: | ------: |
| Quantity    |    2.95 |      3 |       5 |       1 |
| UnitPrice   |  356.41 | 364.21 |  699.93 |   11.39 |
| ItemsInCart |    5.49 |      5 |      10 |       1 |
| TotalPrice  | 1053.97 | 823.62 | 3456.40 |   11.39 |

---

## 📈 Key Findings

### 🛒 Quantity

The average quantity ordered is approximately **2.95 items**, with a median of 3.

This indicates that customers generally place relatively small quantity orders.

### 💰 Unit Price

The average unit price is approximately **356.41**, while the median is **364.21**.

The unit price ranges from **11.39 to 699.93**.

### 🧺 Items in Cart

The average number of items in the cart is approximately **5.49**, with a median of 5.

### 💵 Total Price

The average order value is approximately **1053.97**, while the median is **823.62**.

The higher mean compared with the median suggests the presence of some higher-value orders.

---

## 📦 Product Analysis

The product-wise order analysis shows:

* **Printer:** 181 orders
* **Tablet:** 179 orders
* **Chair:** 178 orders
* **Laptop:** 173 orders
* **Desk:** 170 orders
* **Monitor:** 163 orders
* **Phone:** 156 orders

**Printer** had the highest number of orders, while **Phone** had the lowest.

---

## 🚚 Order Status Analysis

| Order Status | Orders |
| ------------ | -----: |
| Cancelled    |    250 |
| Returned     |    247 |
| Pending      |    237 |
| Shipped      |    235 |
| Delivered    |    231 |

Cancelled orders were the most common category, while delivered orders had the lowest count among the five statuses.

---

## 📅 Monthly Sales Trend

The monthly TotalPrice analysis shows considerable variation throughout the year.

* **Highest:** June – approximately **170,616.13**
* **Lowest:** September – approximately **69,321.65**
* **Total:** approximately **1,264,761.96**

This indicates that sales performance varies significantly across different months.

---

## 💳 Payment Method Analysis

The analysis shows the following order counts:

| Payment Method | Orders |
| -------------- | -----: |
| Online         |    258 |
| Cash           |    246 |
| Credit Card    |    234 |
| Debit Card     |    232 |
| Gift Card      |    230 |

**Online payment** was the most frequently used payment method.

---

## 🎟️ Coupon Analysis

The most frequently used coupon was:

* **FREESHIP:** 312 orders
* **None:** 308 orders
* **WINTER15:** 293 orders
* **SAVE10:** 287 orders

---

## 📣 Referral Source Analysis

| Referral Source | Orders |
| --------------- | -----: |
| Instagram       |    259 |
| Email           |    250 |
| Google          |    241 |
| Facebook        |    228 |
| Referral        |    222 |

**Instagram** generated the highest number of orders among the listed referral sources.

---

## 🔗 Correlation Analysis

The correlation analysis identified the following relationships:

* **UnitPrice ↔ TotalPrice:** approximately **0.717**
* **Quantity ↔ TotalPrice:** approximately **0.615**
* **ItemsInCart ↔ TotalPrice:** approximately **0.393**

The strongest positive relationship was between **UnitPrice and TotalPrice**.

---

## ⚠️ Outlier Analysis

The TotalPrice distribution contains some potential high-value outliers.

These observations should not automatically be removed because they may represent genuine high-value customer orders.

---

## 💡 Business Insights

The EDA provides several useful insights:

1. Customers generally order around **3 items per order**.
2. **UnitPrice** has the strongest positive relationship with **TotalPrice**.
3. June recorded the highest monthly order value.
4. September recorded the lowest monthly order value.
5. Printer had the highest number of orders.
6. Cancelled orders were more common than delivered orders.
7. Instagram was the leading referral source.
8. Online payment was the most frequently used payment method.
9. A few high-value orders may require further investigation as potential outliers.

---

## ✅ Conclusion

This exploratory data analysis helped identify important patterns in customer orders, product performance, pricing, payment methods, and purchasing behavior.

The analysis demonstrates how Excel-based EDA can be used to transform raw e-commerce data into meaningful insights that can support business decision-making.

---

## 👩‍💻 Project

**Project:** DecodeLabs Project 2 – Exploratory Data Analysis
**Tool:** Microsoft Excel
**Dataset Size:** 1,200 records
**Focus:** E-commerce Data Analysis
