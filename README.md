# uber-fare-analysis-kigali-2025
A Power BI and Python-based analysis of Uber fares in Kigali using data visualization and distance computation.

# 🚕 Uber Fare Analysis – Kigali 2025

## 📊 Project Overview

This project focuses on analyzing Uber fare data using **Python (Jupyter Notebook)** and **Power BI** to uncover insights and visualize trends in ride pricing, pickup locations, payment types, and more.

The project follows a typical **data analyst workflow**: cleaning raw data, transforming it for analysis, building a data model, and designing interactive dashboards.

---

## 🔧 Tools Used

- 🐍 **Python (Jupyter Notebook)** – Data cleaning and transformation
- 📈 **Power BI** – Data modeling and interactive visualization
- 📁 **CSV** – Data source format
- 🌐 **GitHub** – Project documentation and version control

---

## 🧹 Step 1: Data Cleaning in Python

The dataset was cleaned using Python libraries including:
- `pandas` for handling missing values and formatting datetime
- `datetime` for converting and manipulating time columns
- Removal of null or incorrect latitude/longitude
- Extracted features like:
  - `pickup_date`
  - `pickup_hour`
  - `day_name`
  - `month_name`

The cleaned dataset was saved as `cleaned_uber_fares.csv`.

---

## 🔗 Step 2: Power BI Data Modeling

**Model Relationships:**
- Connected `uber_fare[pickup_date]` with `Date[date]`
- Set cardinality to `One to Many`
- Used the `Date` table to filter Uber data for time-based insights

**Relationships created:**


---

## 📊 Step 3: Dashboard Visualizations

The Power BI dashboard includes:

| Visual | Description |
|--------|-------------|
| 📍 **Map** | Displays pickup distribution based on latitude/longitude |
| 📅 **Line Chart** | Shows average fare over time |
| 💳 **Column Chart** | Visualizes distribution of payment types |
| ⏰ **Bar Chart** | Trips by hour of the day |
| 🗓 **Month Slicer** | Filters by specific month |
| 🔄 **Interactive Filters** | Used to filter by date, location, and more |

**Bonus Filters Implemented:**
- Fare Amount (Greater than X)
- Payment Type Filter
- Time of Day Filter (Morning, Afternoon, Evening, Night)

---

## 🎯 Key Insights

- 🕗 Most rides happen between **4 PM and 7 PM**
- 💰 Cash payments are the most common
- 🗺 Central Kigali shows the highest pickup activity
- 📉 Some days have significant drops in ride activity — possibly weekends or holidays

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `Uber_Data_Cleaning.ipynb` | Jupyter notebook for data cleaning |
| `cleaned_uber_fares.csv` | Cleaned data used for Power BI |
| `UberFareAnalysis.pbix` | Power BI dashboard file |
| `README.md` | This project documentation |

---

## 🧠 Project Learnings

This project helped me practice:

- Real-world data cleaning in Python
- Power BI relationships and model building
- Interactive report and dashboard design
- Storytelling with data insights

---

## 📍 Next Steps (Optional)

- Add forecast or trend lines for future fare prediction
- Use DAX to calculate KPIs like average fare per day or trip duration

---

## 📬 Contact

👤 **KAYIRANGA Deus**  
📧 Email:deuskayiranga12@gmail.com  
📍 Adventist University of Central Africa  
📘 Student Project – 2025  
