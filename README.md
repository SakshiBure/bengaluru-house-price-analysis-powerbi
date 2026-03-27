# 🏠 Bengaluru House Price Dashboard

📊 A Power BI dashboard that analyzes real estate trends in Bengaluru, helping users understand pricing patterns, location insights, and investment opportunities.

---

## 🚀 Project Overview

This project provides an interactive visualization of Bengaluru housing data, focusing on:

- 📈 Price trends
- 📍 Location-wise analysis
- 🏘️ Property type distribution
- 💰 Investment insights

---

## 📸 Dashboard Preview

![Dashboard Preview](Images/dashboard_preview.png)

---

## 📊 Key Insights

- 💰 Average Property Price: ₹112.57 Lakhs
- 🏡 Total Listings: 13,000+
- 📈 Price Growth: 3.06%
- 📍 Highest Price Area: Cubbon Road

---

## 📌 Features

- 🔍 Price Range Filter (Interactive)
- 📊 Market Value by Availability
- 📍 Location-wise Price Map
- 🏘️ Area Type Distribution
- 📈 Investment Analysis by Property Size

---

## 🛠️ Tools & Technologies

- Power BI
- Excel
- DAX (Data Analysis Expressions)

---

## 📂 Dataset

The dataset includes:
- Property price
- Location
- Area type
- Availability
- Size (BHK)

---

## 📈 DAX Measures Used

```DAX
Average Price = AVERAGE(House[price])

Total Listings = COUNT(House[id])

Price Growth % = 
DIVIDE(
    (MAX(House[price]) - MIN(House[price])),
    MIN(House[price])
)

Avg Price per Sqft = AVERAGE(House[price_per_sqft])
```

---

## 🎯 Business Use Case

This dashboard helps:
- 🏢 Real estate investors
- 🏡 Home buyers
- 📊 Data analysts

Make data-driven decisions based on pricing and location trends.

---

## 👩‍💻 Author

Sakshi Bure  
Aspiring Data Analyst

---

## ⭐ If you like this project, give it a star!
