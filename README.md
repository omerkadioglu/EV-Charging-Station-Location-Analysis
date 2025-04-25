# Service and Charging Type Analysis at EV Charging Stations - DSA210 Project

## **Project Description**
This project aims to analyze whether the services offered at electric vehicle (EV) charging stations (such as parking, restaurants, Wi-Fi) are associated with the station's charging type – fast (DC) or slow (AC).  
Using real-world data, the study will investigate the impact of service variety on charging type through data science methods.

## **Objectives**
- **Charging Type Analysis:** Determine the distribution of fast (DC) and slow (AC) charging stations.  
- **Service Analysis:** Analyze the types and frequencies of services offered at charging stations.  
- **Relationship Examination:** Test the relationship between available services and charging type (AC/DC).  
- **Data Science Application:** Apply data cleaning, exploratory analysis, hypothesis testing, and visualization using Python.

## **Motivation**
Charging speed and additional services are critical factors for EV drivers when choosing a charging station.  
This project aims to provide data-driven insights to inform future station planning and infrastructure development.

## **Dataset**
The dataset includes information about EV charging stations in Turkey, such as:
- Name
- Coordinates (latitude/longitude)
- Charging type (AC/DC)
- Available services (parking, restaurants, Wi-Fi, shopping, etc.)
- Operational hours
- Current status (active, under maintenance, planned)

## **Tools and Technologies**
- **Python** – Core language for data processing and analysis  
- **Pandas** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **SciPy** – Hypothesis testing (Chi-square test)  
- **Jupyter Notebook** – Documentation and analysis

## **Analysis Plan**
1. **Data Collection and Cleaning:**  
   - Extract and process relevant fields from the dataset.json file.

2. **EDA (Exploratory Data Analysis):**  
   - Analyze the distribution of fast (DC) and slow (AC) charging stations.
   - Visualize the frequency of services across different charging types.

3. **Hypothesis Testing:**  
   - Perform chi-square tests to assess the association between services and charging types.

4. **Conclusions and Interpretations:**  
   - Identify which services are more critical for fast charging stations.

## **Expected Outcomes**
- Comparative analysis between fast and slow charging stations based on services offered
- Statistical relationship assessment between services and charging types
- Visualizations: bar charts, heatmaps, etc.

This project aims to produce data-driven strategies for the improvement of EV charging station infrastructures.