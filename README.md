# 🚖 Uber Fare Dataset Analysis using Python & Power BI

This project analyzes the Uber Fares Dataset to uncover key insights about fare patterns, trip volume, and time-based trends using Python and Power BI.

## 🎯 Objective

The aim of this project was to analyze the **Uber Fares Dataset** to derive insights related to:
- Fare distribution patterns  
- Ride distances  
- Temporal ride behavior (hourly, daily, monthly trends)  
- Identifying busiest periods  
- Creating an interactive Power BI dashboard  
- Recommending data-driven insights to improve Uber operations


## 🧰 Tools Used

- 🐍 Python (Jupyter Notebook) – Data cleaning, EDA, and feature engineering  
- 📊 Power BI – Data modeling, visualization, and dashboarding  
- 📁 CSV – Intermediate cleaned data file format  
- 🌐 GitHub – Documentation, version control, and project submission


## 📥 Dataset

- **Source**: [Uber Fares Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/uber-fares-dataset)
- **File Used**: `uber.csv`  
- The dataset contains:
  - `fare_amount`, `pickup_datetime`, `pickup_latitude`, `pickup_longitude`, `dropoff_latitude`, `dropoff_longitude`, `passenger_count`


## 🧼 1. Data Understanding & Preparation

### ✅ Steps Taken:
- Loaded dataset into Pandas using Python  
- Assessed structure (200,000 records × 9 columns)  
- Checked and handled missing values (2 missing drop-off coordinates)  
- Cleaned data types and removed/filtered invalid entries  
- Exported cleaned dataset as `cleaned_uber_fares.csv` for Power BI


## 📊 2. Exploratory Data Analysis (EDA)

### 📌 Summary Statistics:
- Computed mean, median, mode, standard deviation, range, and quartiles  
- Identified outliers using visualizations (box plots and scatter plots)

### 📈 Visuals Created:
- Fare Amount vs. Distance (Scatter plot)  
- Fare Distribution (Histogram)  
- Correlation heatmap of numerical features


## 🛠️ 3. Feature Engineering

- Extracted new time-based features:
  - `pickup_hour`, `pickup_day`, `pickup_month`, `pickup_date`  
- Created distance using Haversine formula
  
- Saved enhanced dataset to `enhanced_uber_fares.csv` for Power BI


## 📉 4. Power BI Analysis

### 🚦 Visualizations Built:
- Monthly and hourly fare patterns  
- Distance vs. fare comparisons  
- Peak/off-peak trend lines  
- Fare summary by passenger count  
- Time-series trend line of fare over months  
- Filled Map: Geographic distribution using pickup/dropoff points  

### 🔍 Filters and Drill-downs:
- Enabled slicers for hour, day, month, and passenger count  
- Latitude/Longitude mapped with "Do Not Summarize" setting


## 📊 5. Power BI Dashboard

- ✔️ Clean UI with consistent formatting  
- ✔️ Histograms and boxplots for fare distribution  
- ✔️ Map visuals displaying ride locations  
- ✔️ Responsive filters for interactivity  
- ✔️ Professional layout for insights and storytelling

📸 Screenshots:
- Data Load
  
<img width="1871" height="889" alt="Screenshot 2025-07-24 185654" src="https://github.com/user-attachments/assets/9c14e0a7-60dd-4528-bc01-2af5c34a42e2" />

- Dashboard Visuals (fare trends, maps, etc.)

<img width="1216" height="658" alt="Screenshot 2025-07-24 141608" src="https://github.com/user-attachments/assets/333084a0-62c1-477c-87f4-2dcadbf3ef99" />

## 📑 6. Analytical Report

### 🧾 Introduction
This project aims to uncover hidden patterns in Uber’s NYC fare data and build a data-driven dashboard for strategic decision-making.

### 📍 Methodology
- Used Python for data cleaning and preparation  
- Used Power BI for dashboard development  
- Enhanced dataset with new features and columns  
- Cleaned outliers and ensured data validity  

### 📊 Analysis & Results
- Most rides happen between 4 PM–8 PM (peak hours)  
- Fare tends to increase with distance, but has some exceptions (outliers)  
- Few multi-passenger rides; most trips involve 1 passenger  
- Map reveals high-density pickup areas in central NYC

### 🧠 Recommendations
- Improve service availability during evening hours  
- Introduce promotions for long-distance low-fare trips  
- Consider optimizing routes in fare-dense regions


## 📂 Deliverables

- ✅ Power BI Dashboard File: `uber_fare_analysis.pbix`  
- ✅ Cleaned Dataset: `cleaned_uber_fares.csv`  
- ✅ Screenshots Folder: `/screenshots`  
- ✅ Python Notebook: `Uber_Fare_EDA.ipynb`  
- ✅ README File (this document)



## ✅ Final Notes

- The project fulfills all six assignment requirements  
- Interactivity, EDA, and business insight goals achieved  
- Dashboard and report aligned with professional standards



> ✨ Thank you for reviewing my Uber Fare Analysis Project! ✨  
> Wishing you a data-driven future ahead!

