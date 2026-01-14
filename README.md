# Highcloude-airlines-analysis-
## 📌 Project Overview
This project focuses on analyzing airline operational performance using historical flight data.  
The primary goal is to evaluate how efficiently airlines utilize available seat capacity (Load Factor), identify top-performing carriers and routes, analyze passenger preferences, and present insights through an interactive dashboard to support business decision-making.

This project was completed as part of a **Data Analytics Internship (High Clouds Case Study)** and simulates real-world airline industry analysis.

---
## 🎯 Business Objectives
- Measure airline efficiency using **Load Factor**
- Identify **top carriers** based on passenger preference
- Analyze **route performance** (from–to city)
- Understand flight distribution across **distance groups**
- Compare **weekday vs weekend** performance
- Build an **interactive dashboard** for stakeholders

---
## 📊 Dataset Description
The project uses **structured airline flight data** consisting of:

### Main Dataset
- Year, Month, Day  
- Carrier Code  
- Origin & Destination (Country, State, City)  
- Available Seats  
- Transported Passengers  
- Distance  
- Payload  

### Supporting Dimension Tables
- Airlines  
- Aircraft Types & Groups  
- Carrier Groups  
- Carrier Operating Region  
- Origin & Destination Markets  
- Distance Groups  
- Flight Types  

Dimension tables were used to convert coded values into meaningful business attributes using lookups and relationships.

---
## 🛠 Tools & Technologies Used
- **Microsoft Excel** – Data cleaning, preprocessing, VLOOKUPs, KPI calculations  
- **SQL (Structured Data)** – Main airline dataset  
- **Dashboard Tool (Excel / BI Tool)** – Visualization & interactive analysis  

---
## 🔧 Data Cleaning & Preprocessing
- Created a proper **Date field** from Year, Month, and Day
- Derived time-based features:
  - Year
  - Month Number & Month Name
  - Quarter (Q1–Q4)
  - Year-Month (YYYY-MMM)
  - Weekday Number & Weekday Name
  - Financial Month & Financial Quarter
- Validated missing values and removed inconsistencies
- Standardized coded fields using dimension tables

---
## 📐 Key Metrics (KPIs)

### 🔹 Load Factor
Load Factor (%) = (Transported Passengers / Available Seats) × 100

yaml
Copy code

Load factor was calculated at:
- Yearly level
- Quarterly level
- Monthly level
- Carrier-wise level
- Weekday vs Weekend level

---

## 📈 Analysis Performed

### 1️⃣ Time-Based Load Factor Analysis
- Yearly, quarterly, and monthly trends
- Identified stable load factor between **75%–78%**

### 2️⃣ Carrier Performance Analysis
- Load factor comparison by carrier
- Passenger preference analysis (Top 10 carriers)

### 3️⃣ Route Analysis
- Identified top **from–to city routes** based on number of flights
- Highlighted high-demand city pairs

### 4️⃣ Distance Group Analysis
- Categorized flights into distance groups
- Short-haul routes (<500 miles) had the highest number of flights

### 5️⃣ Weekday vs Weekend Analysis
- Weekday Load Factor: **~76.7%**
- Weekend Load Factor: **~77%**
- Very minimal variation indicating consistent demand

---

## 📊 Dashboard Features
- KPI cards:
  - Total Payload
  - Available Seats
  - Total Carriers
  - Total Passengers
  - Load Factor %
- Visuals:
  - Load Factor by Year
  - Load Factor by Carrier
  - Top Routes by Flights
  - Top Carriers by Passenger Preference
  - Distance Group Analysis
- Interactive Filters:
  - Year
  - Quarter
  - Month
  - Origin Country
  - Destination Country
  - Carrier Name

---

## 💡 Key Insights
- Airlines maintain a stable load factor indicating efficient capacity utilization
- Large carriers dominate passenger volume due to extensive route networks
- Short-haul routes generate the highest flight frequency
- Demand is consistent across weekdays and weekends

---

## 📌 Business Impact
- Helps airlines optimize seat capacity
- Supports route planning and operational efficiency
- Enables data-driven decisions for management
- Identifies underperforming routes and carriers

---

## 🚀 Future Improvements
- Include revenue and cost data
- Add delay and cancellation metrics
- Build predictive models for demand forecasting
- Automate data refresh and reporting

---
🔗 Dashboard Previews
This project focuses on KPI-driven analysis aligned with the business objective. A single integrated dashboard was developed to track and visualize key KPIs. Supporting tools and files were used for data preparation, querying, and presentation.

* Quick View (PDF -no Download needed)
Tool	View Link
Power BI	🔗 View Power BI Dashboard (PDF)
Tableau	🔗 View Tableau Dashboard (PDF)
Excel	🔗 View Excel Dashboard (PDF)
* Full Interactive Files (Download)
Tool	View Link
Power BI	🔗 View Power BI Dashboard
Tableau	🔗 View Tableau Dashboard
Excel	🔗 View Excel Dashboard
Sql	🔗 View Excel Dashboard
📌 Please replace the placeholder links with shareable Google Drive or OneDrive links.

📂 Data Source
Dataset: 📦 Olist Brazilian E-Commerce Public Dataset - Kaggle


---
## 👤 Author
**Your Name**  
Data Analyst Intern  

---

## 📎 Note
This project is for educational and analytical purposes and uses historical airlin
