# Electric Vehicle Charging Station Location Analysis - DSA210 Project

## **Project Overview**
This project aims to analyze the locations of electric vehicle (EV) charging stations to evaluate their proximity to highways, high-traffic areas (shopping malls, business centers, etc.), and operational hours.

By performing **geospatial data analysis**, this study will provide data-driven recommendations for optimizing station placement. Additionally, it will investigate how operational hours impact station usage.

## **Objectives**
- **Location Analysis:** Assess the proximity of charging stations to **highways, city centers, malls, and business districts.**  
- **Accessibility Evaluation:** Measure ease of access to stations and suggest optimal locations.  
- **Operational Hours Impact:** Analyze the difference in usage between **24-hour stations** and those with restricted operating hours.  
- **Applying Data Science Techniques:** Utilize Python for data processing, analysis, and visualization.  

## **Motivation**
With the increasing adoption of EVs, strategically placing charging stations is crucial. This project will use **data science techniques** to analyze and optimize station locations for maximum efficiency.

- **Urban Planning Contribution** – Identify optimal station locations near residential areas and highways.  
- **Improved Driver Experience** – Help EV drivers find the most convenient charging locations.  
- **Business Efficiency** – Understand how operational hours impact station utilization to provide recommendations for operators.  

## **Dataset**
The dataset will include:
- **Public APIs:** Charging station locations, working hours, and service details.  
- **Web Scraping:** Extracting location data from map-based platforms.  
- **Additional Data Sources:** Traffic congestion and population density datasets for richer insights.  

Key variables include **station name, coordinates (latitude/longitude), operational hours, and distance to highways.**

## **Tools and Technologies**
- **Python** – Core programming language for data analysis.  
- **Pandas & Geopandas** – Data cleaning and geospatial analysis.  
- **Folium & Matplotlib** – Visualizing station distributions on maps.  
- **Scikit-Learn** – Clustering algorithms (K-Means) to optimize station placement.  

## **Analysis Plan**
### **1. Data Collection and Preparation**
- Collect a dataset containing charging station locations and operational hours.  
- Retrieve data via APIs or web scraping and clean the dataset.  

### **2. Geospatial Analysis and Mapping**
- **Visualizing on Maps:** Use Folium to display the distribution of stations across urban areas.  
- **Highway Proximity Analysis:** Calculate the distance of charging stations from major highways.  

### **3. Usage vs. Operational Hours**
- Compare usage patterns between **24-hour stations and limited-hour stations.**  
- Analyze the effect of operational hours on station occupancy.  

### **4. Optimization and Recommendations**
- Use clustering algorithms (K-Means) to identify **optimal locations for new stations.**  

## **Expected Outcomes**
- **A heatmap showing the proximity of charging stations to highways and business centers.**  
- **Graphs demonstrating the impact of operational hours on station usage.**  
- **Clustered recommendations for new charging station placements.**  

This project aims to provide **data-driven recommendations** for urban planners and EV charging station operators to improve accessibility and efficiency.
