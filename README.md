# Washington Crime Data Analysis

---

## Project Overview
A comprehensive Power BI dashboard analyzing crime patterns in Washington, D.C., focusing on crime trends, severity, resolution rates, and geographical crime hotspots. This project aims to provide actionable insights for law enforcement and policymakers.

✔ Live Dashboard Link: [Washington Crime Dashboard](https://app.powerbi.com/reportEmbed?reportId=cdfb6b15-e819-449e-a95e-d91dc68d7862&autoAuth=true&ctid=254ba93e-1f6f-48f3-90e6-e2766664b477)  

_Note: Due to publishing restrictions, the player and team visuals are not visible in the embedded version of the dashboard._  

![Power BI Dashboard](assets/images/Washington%20Crime%20Dashboard.png)

---

## 📌 Table of Contents
1. [Problem Statement](#problem-statement)
2. [Objective](#objective)
3. [Dashboard Design](#dashboard-design)
   - [Home Page](#home-page)
   - [Crime Trends](#crime-trends)
   - [Geographical Analysis](#geographical-analysis)
   - [Crime Severity & Resolution](#crime-severity--resolution)
4. [Tools Used](#tools-used)
5. [Codes Used (DAX Measures)](#codes-used-dax-measures)
6. [Analysis & Insights](#analysis--insights)
   - [Key Takeaways](#key-takeaways)
   - [Recommendations](#recommendations)
7. [Connect with Me](#connect-with-me)

---

## Problem Statement
Crime data is often vast, complex, and difficult to interpret, making it challenging for policymakers, law enforcement, and communities to make data-driven decisions. Understanding when, where, and how crimes occur is essential to improving crime prevention, resource allocation, and public safety.

---

## Objective
This Washington Crime Dashboard was built to analyze crime trends, severity, and geographical distribution to help:
1. Identify crime patterns by time, location, and type.
2. Measure crime severity using UCR rankings.
3. Assess police efficiency through crime clearance rates.
4. Pinpoint high-crime neighborhoods using geospatial analysis.
5. Provide actionable insights for crime prevention and safety measures.


---

## Dashboard Design
The Washington Crime Dashboard is structured into four pages, each focusing on specific crime insights.

### Home Page
Purpose: Provides an overview of key crime metrics at a glance.
- KPI Cards: Total Crimes, Crime Rate, Weapon-Related Crimes, Average Resolution Time.
- Visuals:
  - Crime Trends by Time of Day (Line Chart)
  - Top 5 Most Common Crime Types (Bar Chart)
  - Top 10 Crime Hotspots (Treemap)
- Key Takeaways & Recommendations section.

### Crime Trends
Purpose: Analyzes how crime patterns change over time.
- Visuals:
  - How Crime Trends Change Over Time (Line Chart)
  - How Crime Types Have Changed Over Time (Stacked Column Chart)
  - Are Crimes Being Solved Faster Over Time? (Line & Bar Chart)
- KPI Cards:
  - Daily Average Crimes Reported
  - Most Frequently Reported Crime
  - % of Crimes Occurring at Night

### Geographical Analysis
Purpose: Visualizes crime distribution using maps.
- Visuals:
  - ArcGIS Heatmap (Crime Hotspots)
  - Crime Rate by Police Service Area (Card)
  - Most Common Crime in Selected Area (Card)
  - Highest Crime Neighborhood (Card)

### Crime Severity & Resolution
Purpose: Evaluates the severity of crimes and their resolution rates.
- Visuals:
  - Crime Severity Index by Crime Type (Bar Chart)
  - Crime Rate by Police District (Bar Chart)
  - Crime Resolution Status by Crime Type (Bar Chart)
- KPI Cards:
  - Most Severe Crime Type
  - Crime Severity Index
  - Average Resolution Time
  - Crime Clearance Rate (%)

---

## Tools Used
| Tool | Purpose |
|------|---------|
| Power BI | Data Visualization & Dashboard Creation |
| DAX (Data Analysis Expressions) | Custom calculations & measures |
| ArcGIS | Geospatial crime mapping |
| GitHub | Version Control & Project Documentation |
| ChatGPT | Assisted in refining dashboard structure & DAX troubleshooting |

---

## Codes Used (DAX Measures)
Below are the DAX measures used in the dashboard, along with their purposes.

### Crime Trend & Overview Measures
- `_Total_Crimes` → Counts total crime incidents.
- `_Crime_Rate` → Measures crime rate per 1,000 people.
- `_Crimes_by_Time_of_Day` → Summarizes crimes based on shift (Midnight, Day, Evening).
- `_Top_5_Crime_Types` → Identifies the most frequent crime types.

### Geographical Analysis Measures
- `_Crimes_in_Selected_Area` → Counts crimes in a selected police district.
- `_Crimes_Per_PSA` → Calculates crime density per Police Service Area.
- `_Most_Common_Crime_Selected_Area` → Finds the top crime type in a filtered area.
- `_Top_Crime_Neighborhood` → Identifies the highest crime neighborhood.

### Crime Severity & Resolution Measures
- `_Crime_Severity_Index` → Weighs crimes based on severity rankings.
- `_Crime_Clearance_Rate` → Calculates the percentage of resolved cases.
- `_Resolution_Time` → Averages the number of days it takes to resolve a case.
- `_Crime_Resolution_Rate_Per_District` → Measures resolution rates by police district.

---

## Analysis & Insights
### Key Takeaways
- Crimes peak in the evening, with Theft/Other being the most reported crime.
- Clusters 2, 23, and 25 report the highest crime rates.
- 92.66% of cases are resolved, but violent crimes take longer to resolve.
- Weapon-related crimes pose a significant safety risk in some areas.

### Recommendations
- Enhance anti-theft measures: Since property crimes dominate, authorities should increase surveillance in high-risk areas.
- Improve response time: Crimes with longer resolution times may require additional investigative resources.
- Community awareness: Education and stricter monitoring can help reduce firearm-related incidents.

---

## Feedback & Suggestions
I’m just starting my Data Analytics career transition journey, and this is my first challenge. I know I have a long way to go, and I’d love to hear your feedback and suggestions to improve my analysis! Feel free to share your thoughts.  

---

## Connect with Me
📂 **GitHub Profile**: [github.com/aeronabrahan](https://github.com/aeronabrahan)  
🔗 **LinkedIn Profile**: [linkedin.com/in/jagabrahan](https://linkedin.com/in/jagabrahan)  
📧 **Email Address**: [aerongabrahan@gmail.com](mailto:aerongabrahan@gmail.com)  

---
