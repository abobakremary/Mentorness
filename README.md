# **Airplane Crashes Analysis (1908-2023)**

[![Screenshot 2024-08-30 004152](https://github.com/user-attachments/assets/f28b94bb-ff45-4228-8873-1200820f6de0)](https://public.tableau.com/app/profile/abobakr.emary/vizzes)

*Click the image above to view the interactive dashboard.*

## **Problem Statement**
This project is part of an internship aimed at conducting a comprehensive analysis of airplane crashes and fatalities spanning from 1980 to 2023. The dataset encompasses crucial information such as crash dates, locations, operators, flight details, aircraft types, and fatality statistics. The primary goal is to utilize Tableau for interactive visualizations and gain in-depth insights to understand patterns, contributing factors, and trends in aviation incidents. The findings aim to provide stakeholders with valuable information to enhance aviation safety and mitigate risks.

## **Project Objectives**
### **1. Temporal Analysis**
- **Goal:** Explore temporal trends in airplane crashes over the years.
- **Focus:** Identify patterns in the frequency and severity of incidents.
  
### **2. Geospatial Analysis**
- **Goal:** Visualize crash locations on a map to identify hotspots.
- **Focus:** Analyze the distribution of incidents across different regions.

### **3. Operator Performance**
- **Goal:** Evaluate the safety records of different operators and airlines.
- **Focus:** Identify operators with higher incident rates.

### **4. Aircraft Analysis**
- **Goal:** Analyze the involvement of specific aircraft types in incidents.
- **Focus:** Examine the relationship between aircraft registration and crash occurrences.

### **5. Fatality Trends**
- **Goal:** Explore trends in passenger and crew fatalities.
- **Focus:** Investigate factors contributing to fatalities.

### **6. Route Analysis**
- **Goal:** Analyze incident patterns on specific flight routes.
- **Focus:** Identify routes with a higher likelihood of incidents.

## **Data & Tools**
### **Data Sources:**
- **Dataset:** Mentorness Data Analysis Internship.

### **Tools Used:**
- **Data Cleaning:** Excel, ChatGPT for automated data verification.
- **Data Visualization:** Tableau for creating interactive dashboards and visualizations.
- **Data Analysis:** Excel for exploratory data analysis (EDA) and trend identification.
- **Version Control:** GitHub for project management and version control.

## **Data Cleaning Process**
The data cleaning process involved several key steps:
1. **Handling Missing Values:** Missing values were identified and appropriately handled. For instance, missing data in critical columns like `Location`, `Operator`, and `Aircraft Type` were filled with "Unknown" where applicable.
2. **Standardization:** Dates were converted into a standardized datetime format, and inconsistencies in categorical data were corrected to ensure uniformity.
3. **Adding Contextual Information:** A new column named `Country` was added to provide contextual information about the location of each incident, thereby enhancing the dataset's analytical depth.
4. **Verification:** Data consistency was verified using Excel and automated tools like ChatGPT to ensure that entries were correctly categorized, especially for countries and states.

These cleaning and enrichment efforts ensured that the dataset was well-prepared for accurate analysis and informed decision-making in aviation safety.

## **Analysis and Insights**
### **1. Geospatial Analysis**
By visualizing crash locations on a world map, hotspots of incidents were identified. This allowed stakeholders to focus their attention on regions with higher incident rates. The distribution of incidents across different regions was also analyzed, enabling a prioritization of safety measures and more effective allocation of resources.

### **2. Fatality Trends**
The analysis of trends in passenger and crew fatalities revealed fluctuations over the years, reflecting the dynamic nature of aviation safety. Interactive visualizations provided stakeholders with a deeper understanding of how fatalities have evolved, offering insights into the effectiveness of safety measures and the impact of regulatory changes on reducing fatalities in airplane incidents.

### **3. Temporal Analysis**
Temporal analysis revealed fluctuations in the frequency of airplane crashes over the years, with notable spikes and declines. Further investigation into these trends helped identify potential factors contributing to variations in crash frequency, providing a basis for proactive safety measures. The distribution of fatalities across different incident types over time was also examined.

## **Summary**
The analysis of airplane crashes and fatalities from 1980 to 2023, conducted using tools like Tableau, has revealed key insights into aviation safety. Trends were identified, incident severity was assessed, and factors impacting fatalities were pinpointed. The thorough data cleaning process ensured the accuracy of the dataset, and the addition of contextual columns like `Country` enriched the analysis. These findings set the stage for improved aviation safety measures, contributing to a safer air travel environment.
