# Big-Data-Analysis
# ✈️ Airport Data Analysis using PySpark, Pandas & KMeans Clustering

This project performs exploratory data analysis and unsupervised clustering on a dataset of airports using **PySpark** and **scikit-learn**, with data visualizations powered by **Matplotlib**.

## 📌 Project Overview
The goal of this project is to:
- Analyze airport data using distributed computing via PySpark.
- Generate useful insights based on time zones, altitude, and daylight saving categories.
- Apply **KMeans clustering** to group airports geographically.
- Visualize raw data and clusters using **matplotlib**.
  
## 🔧 Tech Stack
- 🐍 Python 3.x
- ⚙️ Apache Spark (PySpark)
- 📊 Pandas & Matplotlib
- 🧠 Scikit-learn (KMeans Clustering)

## 📂 Dataset
The dataset used is a CSV file: `airports data.csv`, which contains metadata about global airports.
Expected columns include:
- `faa`: Airport code
- `name`: Airport name
- `lat`, `lon`: Latitude and longitude
- `alt`: Altitude
- `tz`: Time zone
- `dst`: Daylight saving time indicator

## 🚀 Features Implemented

1. **Schema & Preview**
   - Displays inferred schema and a sample of the dataset.

2. **Airports by Time Zone**
   - Aggregates and sorts airports grouped by time zone.

3. **Altitude Analysis**
   - Displays top 5 highest and lowest altitude airports.

4. **Daylight Saving Time Category Analysis**
   - Counts airports per DST category.

5. **Geospatial Visualization**
   - Plots airports on a longitude vs latitude scatter plot.

6. **KMeans Clustering**
   - Groups airports into 5 geographic clusters.
   - Visualizes clusters with different colors for each group.

## 🖼 Sample Visualizations
### 📍 Raw Airport Distribution  
Shows a scatter plot of all airport locations.
### 🔄 KMeans Clustered Airports  
Visualizes 5 geographic clusters derived from lat/lon using KMeans.


