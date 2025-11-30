# Deloitte--Daikibo-Analysis- in -Tableau
This project involves analyzing telemetry data collected by **Daikibo** using **Tableau**.   The goal is to measure potential downtime across factories and device types, visualize the results, and build an interactive dashboard to identify critical problem areas.

## Steps Performed

### 1. Setup
- Downloaded and installed Tableau Desktop (free trial).
- Registered an account using the same email as the download.
- Imported the dataset (`daikibo-telemetry-data.json`) into Tableau.

### 2. Data Preparation
- Created a **calculated measure field** called `Unhealthy`.  
  - Formula: Assign a value of **10** for every "unhealthy" status.  
  - Represents **10 minutes of potential downtime** since the previous message.

### 3. Visualizations
- **Bar Chart 1:** *Down Time per Factory*  
  - Shows total downtime aggregated by factory.  
- **Bar Chart 2:** *Down Time per Device Type*  
  - Shows downtime aggregated by device type.

### 4. Dashboard Creation
- Combined both charts into a single dashboard.  
- Configured the **first chart (Factory)** as a filter:  
  - Selecting a factory bar filters the second chart to show downtime only for devices in that factory.

### 5. Analysis
- Selected the factory with the **highest downtime**.  
- Captured a **screenshot of the dashboard** showing filtered results.  
- Saved the dashboard and screenshot for submission.

##  Learning Objectives
- Gain hands-on experience with **Tableau Desktop**.  
- Learn how to create **calculated fields** for custom metrics.  
- Build interactive dashboards with **filters and linked charts**.  
- Interpret downtime patterns across factories and device types.  

##  Deliverables
- Tableau workbook 
- Dashboard screenshot highlighting the factory with the most downtime.  
- README documentation (this file).  

## How to Reproduce
1. Download and install Tableau Desktop.  
2. Import the `daikibo-telemetry-data.json` file.  
3. Create the calculated field `Unhealthy` with value = 10 for unhealthy status.  
4. Build bar charts for downtime per factory and per device type.  
5. Combine charts into a dashboard and set the factory chart as a filter.  
6. Select the factory with the most downtime and capture the screenshot.  

---

