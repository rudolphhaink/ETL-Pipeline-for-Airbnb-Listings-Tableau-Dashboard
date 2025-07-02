# 🏡 Airbnb Listings ETL Pipeline

This project demonstrates an end-to-end ETL (Extract, Transform, Load) pipeline for Airbnb listing data.  
It is designed as part of my Data Analyst portfolio to showcase practical data wrangling and preparation skills.  
[Datasource](https://insideairbnb.com/get-the-data/)

---

## 🚀 Project Overview

**Goal:** Clean and prepare raw Airbnb data for analysis and visualization (e.g., in Tableau).  
**Tools Used:**  
- Python (Pandas, NumPy, OS)
- Jupyter Notebook
- Tableau (for final dashboard — coming soon!)

---

## 🔧 ETL Process

The ETL pipeline consists of the following steps:

### 1. **Extract**
- Load raw listing data from a CSV file (`listings.csv`)

### 2. **Transform**
- Drop irrelevant columns (`license`, `availability_365`, etc.)
- Convert date fields to proper datetime format
- Handle missing values (`reviews_per_month`)
- Rename columns for clarity and consistency

### 3. **Load**
- Export the cleaned dataset as `listings_cleaned.csv` for downstream analysis or visualization.

---

## 📊 Tableau Dashboard

A Tableau dashboard based on the cleaned dataset.
[Dashboard](https://public.tableau.com/app/profile/rudolph.haink/viz/AirBnBListings_17512734486760/Dashboard1)

---

## 📁 Project Structure

listings.csv # Raw input data  
listings_cleaned.csv # Cleaned dataset output  
ETL-Pipeline-for-Airbnb-Listings-Tableau-Dashboard.ipynb # Jupyter notebook with the full ETL pipeline  
README.md # Project documentation


---

## ✅ Key Skills Demonstrated

- Real-world data cleaning using pandas
- Managing missing data and data types
- Structuring reproducible Python notebooks
- Preparing datasets for BI tools like Tableau

---

## 📬 Contact

**Author:** Rudolph Haink  
Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/rudolph-haink-a5454564/) or GitHub if you'd like to connect!
