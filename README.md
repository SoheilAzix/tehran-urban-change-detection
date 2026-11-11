# Spatiotemporal Change Detection - Tehran Urban Growth

## Overview
This project focuses on detecting and analyzing spatiotemporal changes in Tehran's urban growth over time. By utilizing satellite imagery and geospatial data, the project aims to map the expansion of urban areas, identify land-use/land-cover (LULC) transitions, and visualize the spatial patterns of Tehran's development.

## Objectives
- To analyze the urban expansion of Tehran across different time periods.
- To classify land cover changes, including built-up areas, vegetation, barren land, and water bodies.
- To generate change detection maps to visualize the spatiotemporal dynamics of urban growth.
- To provide insights into the environmental and infrastructural impacts of rapid urbanization.

## Technologies and Tools Used
- **Programming Language:** Python
- **GIS and Remote Sensing:** Google Earth Engine (GEE), Geopandas, Rasterio, GDAL
- **Data Analysis and Visualization:** Pandas, NumPy, Matplotlib, Folium
- **Machine Learning:** Scikit-learn, TensorFlow

## Data Sources
- Landsat Satellite Imagery (Landsat 5, 8)
- Sentinel-2 Imagery
- OpenStreetMap (OSM) Data

## Methodology
1. **Data Acquisition:** Collecting multi-temporal satellite imagery for the Tehran study area.
2. **Preprocessing:** Cloud masking, atmospheric correction, and image co-registration.
3. **Classification:** Applying image classification algorithms to categorize land cover types.
4. **Change Detection:** Utilizing post-classification comparison and image differencing techniques to identify changes.
5. **Analysis and Visualization:** Generating maps and statistical reports to analyze urban growth trends.

## Project Structure
- `/data`: Raw and processed datasets.
- `/notebooks`: Jupyter notebooks for data exploration and modeling.
- `/src`: Source code for processing and analysis.
- `/results`: Output maps, charts, and final reports.


