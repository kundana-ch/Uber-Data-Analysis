# Uber Data Analysis using Python

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) on Uber ride data to understand ride patterns based on category, purpose, time, day, month, and distance travelled.

The analysis answers real-world business questions such as:
- In which category do people book Uber rides the most?
- For which purpose are Uber rides booked frequently?
- At what time are Uber rides booked the most?
- On which days and months is ride activity higher?
- How long are Uber rides typically?

---

## 📂 Dataset Details
- **Dataset Name:** uber-dataset.csv
- **Rows:** 1156
- **Columns:** 7

### Key Columns
- `START_DATE*` – Ride start date and time  
- `END_DATE*` – Ride end date and time  
- `CATEGORY*` – Business / Personal  
- `START*` – Start location  
- `STOP*` – Stop location  
- `MILES*` – Distance travelled  
- `PURPOSE*` – Purpose of the ride  

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Analysis Performed
- Data cleaning and handling missing values
- Datetime conversion and feature engineering
- Created new features such as:
  - Date
  - Time
  - Day of week
  - Month
  - Day-Night category
- Exploratory Data Analysis (EDA)
- Data visualization using bar plots, line plots, box plots, and histograms

---

## 📊 Key Insights
- Business category accounts for the majority of Uber rides
- Most rides are booked for work-related purposes
- Afternoon is the peak time for Uber bookings
- Fridays have the highest number of Uber rides
- Ride activity varies across different months
- Most Uber rides are short-distance trips, generally between 2 and 10 miles

---

## ✅ Conclusion
This project demonstrates how exploratory data analysis techniques can be applied to real-world Uber ride data. By analyzing ride patterns across time, category, and distance, meaningful insights were derived to understand user behavior and booking trends.

---

## 🚀 Future Scope
- Predict ride demand using machine learning models
- Perform location-based analysis
- Build interactive dashboards using Power BI or Tableau
