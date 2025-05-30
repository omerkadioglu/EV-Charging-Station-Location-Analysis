# EV Charging Stations in Turkey: Geographical and Service-Based Segmentation

## Overview

This project analyzes the landscape of electric vehicle (EV) charging stations in Turkey using detailed real-world data from a major Charging Point Operator (CPO). Our goal is to uncover patterns in accessibility, service diversity, pricing, and operational status, providing actionable insights for operators, policymakers, and EV users.

---

## Motivation

As EV adoption accelerates in Turkey, a robust and accessible charging network is essential. Not only the number of stations but also the **quality and diversity of amenities**—parking, food, WiFi, and more—directly influence user experience and nationwide adoption.  
This project segments and visualizes Turkey’s EV charging ecosystem to highlight strengths and opportunities for further development.

---

## Data Source

- **Primary dataset:** JSON-formatted data provided by [POWERSARJ].
- **Fields:** Station location (city, district, latitude, longitude), AC/DC support, pricing, status, operator, available amenities (parking, restaurant, WiFi, etc.).
- **Location:** `data/ev_charging_stations.json`
- **[Optional]**: Additional public data (city population, EV adoption) may be included for advanced analyses, but the focus remains on the core dataset.

---

## Analysis Plan

1. **Data Preparation**
    - Load and normalize JSON data into a pandas DataFrame.
    - Clean and process features: standardize categories, parse nested amenities/services.
    - Extract key fields: location, station type, power, socket count, price, operator, availability, and amenities.

2. **Exploratory Data Analysis (EDA)**
    - Geographic distribution of stations by city/district.
    - Breakdown by AC/DC, operator, public/private status, online/offline, active/inactive.
    - Amenity/service availability: parking, restaurant, WiFi, restroom, market, playground, etc.
    - Visualizations: interactive maps, bar charts, heatmaps.

3. **Segmentation & Clustering**
    - Cluster stations by service offerings and operational characteristics (e.g., K-means).
    - Identify “typical station types” and underserved segments.

4. **Pricing & Service Analysis**
    - Examine the relationship between kWh pricing and available amenities.
    - Correlation/regression analysis to reveal key drivers.

5. **Results & Recommendations**
    - Highlight regions or station types lacking services/access.
    - Provide actionable recommendations for infrastructure improvement.

---

## Key Questions Addressed

- Where are Turkey’s EV charging stations concentrated?
- Which cities/regions are underserved by public, high-power (DC) chargers?
- How do amenities (parking, restaurant, WiFi) vary by region/operator?
- Is there a significant link between station pricing and amenity diversity?
- Which operators provide the most user-friendly infrastructure?

---

## How to Run

1. **Clone the repository:**
    ```bash
    git clone https://github.com/omerkadioglu/EV-Charging-Station-Location-Analysis.git
    cd EV-Charging-Station-Location-Analysis
    ```
2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3. **Place the data:**
    - Add your JSON file as `data/ev_charging_stations.json`.
4. **Run the analysis:**
    - Open and run `notebooks/analysis.ipynb` in JupyterLab/Notebook to reproduce all results, figures, and tables.

---

## Dependencies

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- plotly (for interactive visualizations)
- jupyterlab (or classic notebook)
- unidecode
- folium (optional, for maps)

All requirements are listed in `requirements.txt`.

---

## Limitations & Future Work

- The dataset does not include historical usage or real charging session data, so user demand is inferred from station attributes.
- Including city/district-level EV adoption or population data could strengthen spatial analysis.
- Future work: Add time-series analysis and user behavioral data as it becomes available.

---

## License

This project is open-source for educational and research purposes.  
If you use or modify the code, please cite the dataset provider ([POWERSARJ]) and this repository.

---