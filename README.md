# 📊 User Activation & Retention Analysis

**User Activation & Retention Analysis** project — a practical **product analytics case study** exploring user behavior within a mobile app, from signup to long-term retention.  
This project showcases proficiency in **Python (data cleaning)**, **SQL (data exploration)**, and **Power BI/Tableau (dashboard visualization)**.

---

## 🎯 Project Objective

The goal of this project is to **analyze and visualize user engagement** across key stages of the product lifecycle:

- How many users activate after signing up?
- What are the most frequent user actions (events)?
- How does user retention change over time?
- Are there behavioral differences by **country**, **age group**, or **device OS**?
- Which features drive engagement among returning users?

---

## 🛠️ Tools & Technologies

| Tool / Technology           | Purpose                                         |
|-----------------------------|-------------------------------------------------|
| **Python (Pandas)**         | Data cleaning & preprocessing                   |
| **SQL**                     | Exploratory data queries                        |
| **Power BI**                | Primary dashboard creation & publishing         |
| **Tableau**                 | Alternate visualization for comparative insights|
| **CSV Dataset (Kaggle)**    | Raw user-level interaction logs                 |

---

## 📁 Dataset Overview

The dataset (sourced from **Kaggle**) contains detailed **mobile app event logs**, including:

- `timestamp`, `user_id`, `age`, `country`, `device_os`, `app_language`
- `session_id`, `event_type` (e.g., click, swipe, share)
- `session_duration_sec`, `memory_usage_mb`
- 20+ additional columns tracking user and technical attributes

---

## 🧹 Data Preprocessing (Python)

The script `analyze_product_funnel.py` was used to prepare clean data for analysis:

- Converted `timestamp` → datetime  
- Normalized and validated `user_id` values  
- Removed missing or duplicate entries  
- Filtered timeframe (2020–2026)  
- Exported processed dataset → `cleaned_mobile_app_data.csv`

---

## 📊 Key Metrics & KPIs

- **Average Events per User**  
- **Top Events by Frequency**  
- **Activation Rate (%)**  
- **User Funnel:** Signup → Activation → Retention  
- **Retention Trend (Daily/Weekly Active Users)**  
- **User Demographics:** Age & Country Distribution  
- **Device OS Usage Share**  
- **Feature Adoption Heatmap**  
- **Avg Memory Usage / Session Duration**

---

## 📈 Dashboards

### 🔷 Power BI Dashboard (Primary)
An interactive dashboard built in **Power BI**, featuring:
- Country & Device OS filters  
- KPI cards and funnel visualizations  
- Signup → Activation → Retention funnel chart  
- Dynamic Power Query transformations  

📸 **Screenshot (Power BI)**  
![Power BI Dashboard](https://github.com/user-attachments/assets/3ecc6151-8e9d-41e4-9c8c-e62c2ec15ecf)

---

### 🟧 Tableau Dashboard (Alternate)
An alternate version designed in **Tableau** using the same dataset:
- DAU trends over time  
- Heatmap of feature adoption  
- KPI cards, funnels, and OS usage analysis  

🔗 **[View Live Dashboard on Tableau Public](https://public.tableau.com/views/UserActivationRetentionDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**


---

## 💡 Learnings & Highlights

- Used **Power Query** for advanced data filtering & transformation.  
- Integrated **Python + SQL** for robust data preprocessing and validation.  
- Designed KPI-driven storytelling dashboards in **Power BI** & **Tableau**.  
- Explored **funnel analysis**, **DAU tracking**, and **user segmentation**.  
- Practiced effective visualization design and cross-tool comparison.


