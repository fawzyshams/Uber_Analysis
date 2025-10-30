# 🚖 Uber Rides Analytics Dashboard

## 📌 Project Overview
This project analyzes **Uber ride booking data** to extract key insights about rides, customers, cancellations, revenue, and vehicle performance.  
The analysis was conducted in **Python (Google Colab)** for data cleaning and preprocessing, and then visualized in **Power BI** using interactive dashboards.

---

## 🧠 Objectives
- Clean and prepare raw ride booking data for analysis.
- Explore booking patterns, customer behavior, and cancellation reasons.
- Visualize insights about ride distribution, vehicle types, revenue, and distances.
- Build an interactive Power BI dashboard for better decision-making.

---

## 🧹 Data Cleaning & Preparation (Python - Colab)
### Steps performed:
1. **Loaded** dataset `ncr_ride_bookings.xlsx` using Pandas.
2. **Explored** the dataset using `.info()`, `.describe()`, and `.isnull().sum()` to understand structure and missing values.
3. **Created** a clean copy of the dataset (`df_clean`).
4. **Handled missing values** using:
   - Group means based on `Vehicle Type`, `Pickup Location`, and `Drop Location`.
   - Filled remaining nulls using overall column means.
5. **Saved** the cleaned dataset to be used in Power BI for visualization.

---

## 📊 Power BI Dashboard
The cleaned dataset was imported into **Power BI**, and four dashboard pages were created:

### 1. **Overview Page**
- Total Rides, Customers, and Booking Value.
- Rides by Booking Status.
- Cancellations breakdown by driver, customer, or issues.
- Monthly ride trends.

### 2. **Vehicle Page**
- Total rides and booking value per vehicle type.
- Average customer and driver ratings.
- Vehicle performance table showing:
  - `Avg CTAT`
  - `Avg VTAT`
  - `Total Booking Value`
  - `Total Ride Distance`

### 3. **Cancellation Page**
- Detailed view of cancellations by type, time, and location.

### 4. **Revenue & Distance Page**
- Insights into distance-based revenue trends.
- Comparison across vehicle types and locations.

---

## 🧱 Data Model (Star Schema)
The data model was designed using a **Star Schema** in Power BI, connecting fact and dimension tables for optimized performance and clear relationships.

---

## 🛠️ Tools & Technologies
- **Python (Google Colab)** – Data cleaning & preprocessing  
- **Pandas, NumPy, Matplotlib** – Data handling and analysis  
- **Power BI** – Dashboard visualization & data modeling  
- **Excel** – Raw data source  

---

## 📈 Key Insights
- The majority of rides were **successfully completed (≈62%)**.  
- **Driver-related cancellations** represented the largest share (~58%).  
- The **“Auto” vehicle type** achieved the **highest booking value and ride distance**.  
- **Average customer rating:** 4.40  
- **Average driver rating:** 4.23  

---

## 📎 Project Files
| File | Description |
|------|--------------|
| `py_analysis.ipynb` | Python data cleaning and preprocessing notebook |
| `clean_data.xlsx` | Cleaned dataset used for Power BI |
| `Uber_Dashboard.pbix` | Power BI dashboard file |
| `star_schema.png` | Power BI data model schema |
| `README.md` | This documentation |

---

## 📷 Dashboard Previews


