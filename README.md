# 📊 App Insights Unlocked – Google Play Store Analysis (Power BI)

## 🚀 Project Overview

This project analyzes Google Play Store app data to understand the key factors that drive app success. Using Power BI, the dashboard explores app ratings, installs, pricing, categories, and genres to uncover trends that can guide product, marketing, and monetization strategies.

The goal is to transform raw app data into **actionable business insights** that help developers build better apps and improve user adoption.

---

## 🎯 Business Problem

With thousands of competing apps on the Play Store, companies need to understand:

* What makes an app successful?
* Which categories and genres attract the most users?
* How do price, ratings, and app size influence installs and engagement?

---

## 🧹 Data Preparation

Data cleaning and transformation were performed in **Power Query**:

* Removed duplicates and handled missing values
* Standardized text fields (categories, genres, etc.)
* Converted text values into numeric fields
* Created new analytical columns:

  * **Installs_Clean** → Numeric installs for analysis
  * **Size_MB** → Numeric app size in MB

---

## 📈 Dashboard Features

The Power BI report includes 5 interactive pages:

1. **Home Overview**

   * KPIs: total apps, installs, genres, categories, average price
   * Top apps by installs
   * Top categories and content rating distribution

2. **App Details (Drill-through)**

   * Deep dive into individual app performance
   * Dynamic page showing selected app or top app by default

3. **Category Analysis**

   * Installs by category
   * Free vs Paid distribution
   * App engagement metrics

4. **Genre Analysis**

   * Installs and app count by genre
   * Average rating and pricing trends

5. **Decomposition Tree**

   * Root-cause analysis of installs by category, genre, type, and app

---

## 🔑 Key Insights

* Over **92% of apps are free**, confirming the dominance of freemium models
* A small number of apps generate **billions of installs** (winner-takes-most market)
* **Games and family-friendly apps** dominate downloads
* Most installs come from **Everyone and Teen audiences (~89%)**
* Engagement and accessibility matter more than pricing for scale

---

## 🛠 Tools & Skills Used

* Power BI (Power Query, DAX, Data Modeling)
* Data Cleaning & Transformation
* Drill-through & Bookmarks Navigation
* KPI Design & Data Storytelling

---

## 📌 Outcome

This dashboard demonstrates how data analytics can help identify market opportunities, optimize app strategy, and support data-driven decision making in the mobile app industry.
