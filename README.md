# Hotel Booking Data Analysis & Revenue Insights

## 📌 Project Overview
This project performs an in-depth exploratory data analysis (EDA) on hotel booking data to uncover meaningful insights related to customer behavior, booking patterns, cancellations, and revenue metrics such as ADR (Average Daily Rate).

The analysis focuses on both **City Hotels** and **Resort Hotels**, helping understand factors influencing pricing, cancellations, room upgrades, and customer segmentation.

---

## 🎯 Objectives
- Clean and preprocess raw hotel booking data
- Handle missing values and outliers
- Perform univariate, bivariate, and multivariate analysis
- Analyze time-series booking trends
- Identify factors influencing ADR and cancellations
- Support business decision-making using statistical and visual insights

---

## 📊 Dataset Information
- **Source:** Hotel Booking Dataset
- **Rows:** ~119,000+
- **Columns:** 32
- **Key Features:**
  - Booking details (lead time, arrival date, stay duration)
  - Customer demographics
  - Market segment & distribution channel
  - ADR (Average Daily Rate)
  - Cancellations and booking changes

---

## 🧹 Data Cleaning & Preprocessing
Key steps performed:
- Removed irrelevant or highly missing columns
- Filled missing values:
  - `children`, `agent` → Mode
  - `country` → "Unknown"
- Dropped `company` column (>93% missing)
- Converted month names to numeric format
- Created new features:
  - `total_stay`
  - `arrival_date`
  - `total_guests`
  - `total_revenue`
  - `room_matched` & `is_upgraded`

---

## 🔍 Exploratory Data Analysis (EDA)

### Univariate Analysis
- ADR distribution
- Lead time distribution
- Market segment and customer type frequency

### Bivariate & Multivariate Analysis
- ADR vs lead time
- ADR vs customer type
- Booking changes vs special requests
- Room upgrades vs room types

### Time-Series Analysis
- Monthly booking trends
- Seasonal demand patterns

---

## 📈 Key Business Insights

- **Direct bookings** offer high ADR with low cancellation rates
- **Online TA** generates high revenue but has higher cancellation risk
- Guests booking **1–6 months in advance** pay higher ADR
- **Special requests** moderately increase ADR
- **Room mismatch rate:** ~12.5%
- **Top nationalities:** Portugal (PRT), UK (GBR), France (FRA)
- Guests making booking changes are **more likely to cancel**

---

## 📌 Statistical Analysis
- Pearson correlation analysis
- Chi-square tests for association
- Correlation heatmaps
- Hypothesis testing for booking behavior

---

## 🛠 Tools & Technologies Used
- **Python**
- **Libraries:**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - SciPy
  - Statsmodels

---

## 🚀 Conclusion
This project demonstrates how data-driven analysis can help hotels optimize pricing strategies, reduce cancellations, enhance customer experience, and identify high-value booking channels. The project was developed as part of my CDAC training, applying real-world data analysis techniques using Python.

---

## 👤 Author
**Akshay Bhadule**  
MCA Graduate | Data Analytics & Python
📧 Email: bhaduleakshay@gmail.com  

---
