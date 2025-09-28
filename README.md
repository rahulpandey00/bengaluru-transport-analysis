

## Project Summary: Identifying Transportation Deserts in Bengaluru
This project is a comprehensive analysis of Bengaluru's public bus transport system, designed to identify and visualize "transportation deserts" — urban areas with high population density but inadequate access to public transit.

By integrating three distinct and complex datasets, the project tells a data-driven story about urban mobility and equity.

Data Integration:

Bus Stop Locations: Extracted from the official BMTC GTFS feed (stops.txt).

Geospatial Boundaries: Utilized the BBMP Ward Shapefile to create a digital map of the city's administrative areas.

Demographics: Leveraged the Primary Census Abstract (PCA_CDB_2918_F_Census.xls) to gather ward-level population data.

Analytical Process:

Data Cleaning: The project involved significant data wrangling, including correcting misaligned columns, handling file path and parsing errors, and standardizing inconsistent naming conventions across datasets.

Geospatial Analysis: A spatial join was performed to accurately count the number of bus stops located within each specific city ward.

Insight Generation: A key metric, "bus stops per 1,000 people," was calculated for each ward by merging the geospatial results with the population data.

Key Finding & Visualization:
The project culminates in a series of choropleth maps that visually represent the findings. The final, most impactful map clearly highlights the underserved wards, providing a data-backed foundation for recommending improvements to the city's public transport network. This analysis successfully pinpoints specific areas where transit resources are not aligned with population needs.

This end-to-end project showcases practical skills in data cleaning, geospatial analysis, data integration, and insightful visualization to address a real-world urban planning challenge.












Tools


