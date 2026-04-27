# Airline Delay Analysis for Online Travel Platforms

##  Project Overview
Flight delays and cancellations are critical factors that directly impact customer satisfaction in online travel platforms. Poor airline performance can lead to negative user experiences, reduced trust, and lower conversion rates.

This project aims to analyze airline delay data to uncover patterns, identify root causes, and provide actionable insights that can help improve decision-making within a travel platform.

---

##  Objectives
- Identify airlines with the highest delay and cancellation risk  
- Analyze the main causes of flight delays  
- Evaluate whether delays are driven by operational or external factors  
- Provide data-driven recommendations to improve customer experience  

---

##  Business Context
As a data analyst in an online travel platform, understanding airline reliability is essential for improving user experience. By identifying high-risk airlines and delay patterns, the platform can optimize flight recommendations and increase user trust.

---

##  Dataset
- Source: Airline Delay Datase
- Link Download: https://www.kaggle.com/datasets/sriharshaeedala/airline-delay 
- Contains information about:
  - Airline carriers  
  - Arrival delays  
  - Cancellation counts  
  - Delay causes (carrier, weather, NAS, security, late aircraft)  

---

##  Tools & Technologies
- Python (Pandas, NumPy)
- SQL (SQLite in Google Colab)
- Data Visualization (Matplotlib, Seaborn)
- Google Colab

---

##  Analysis Process

### 1. Data Cleaning
- Handling missing values  
- Removing duplicates  
- Standardizing column names  
- Validating data types  

### 2. Exploratory Data Analysis (EDA)
- Identifying overall delay patterns  
- Comparing airline performance  
- Understanding distribution of delay causes  

### 3. SQL Analysis
- Identifying high-risk airlines (delay + cancellation)  
- Analyzing root causes of delays per airline  
- Measuring operational delay contribution  

### 4. Visualization
- Scatter plot (risk mapping)  
- Heatmap (delay intensity)  
- Bar chart (operational ratio)  

---

##  Key Insights
- Flight delays are concentrated among a few underperforming airlines  
- Airlines such as WN and AA show high delay and cancellation rates  
- Operational delays (late aircraft) are the dominant cause  
- Around 38.6% of total delays are driven by internal operational issues  
- Delay patterns are systemic, not isolated to specific airlines  

---

## 🚀 Recommendations
- Prioritize airlines with better on-time performance in search results  
- Provide delay risk transparency to users  
- Implement airline risk flagging system  
- Encourage operational improvements through data insights  
