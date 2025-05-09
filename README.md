# Advanced-Geospatial-Analysis-for-Election-Integrity-in-Oyo-State-Nigeria.

This project utilizes geospatial analysis, statistical modeling, and machine learning to examine the 2023 Presidential Election results in Oyo State, Nigeria, and identify potential electoral irregularities.

## Key Objectives

* Detect statistical outliers in voting results using spatial autocorrelation measures.
 
* Identify geographic clusters of irregularities through DBSCAN clustering.
   
* Validate anomalies using machine learning (Isolation Forest).
   
* Contextualize findings through historical and demographic comparisons.

## Methodology

The analysis involves a four-stage pipeline:

1.  **Data Preparation:** Geocoding polling units using Google Maps API and cleaning the dataset.
   
2.  **Spatial Analysis:** Applying HDBSCAN clustering to group polling units and using Local Moran's I and Getis-Ord Gi\* for outlier detection.
   
3.  **Machine Learning Validation:** Training an Isolation Forest model to detect global anomalies.
   
4.  **Contextualization:** Comparing 2023 results with historical data and mapping anomalies to socio-economic indicators.

## Results

Key deliverables include:

* Geocoded dataset with outlier scores.
   
* Prioritized list of high-risk polling units.
   
* Interactive dashboard for visualizing clusters and anomalies : (https://app.powerbi.com/view?r=eyJrIjoiYzNkZWU1ODEtZTI0Ni00MGE1LThmMjQtOGFmMzFjN2RiMDRkIiwidCI6ImFlNmEwMjQwLTRkMmUtNDI4My1hZjFkLWI0MDZkNDg4MDg0YyIsImMiOjh9)
   
* Analytical report with findings and recommendations.

## Impact

This project provides a framework for electoral authorities to efficiently audit irregularities and enhance transparency in the electoral process.
