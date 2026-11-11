
# Spatiotemporal Change Detection - Tehran Urban Growth

## 📌 Overview
This project focuses on detecting and analyzing spatiotemporal changes in Tehran's urban growth over time. By utilizing satellite imagery and geospatial data, the project aims to map the expansion of urban areas, identify land-use/land-cover (LULC) transitions, and visualize the spatial patterns of Tehran's development.

## 🎯 Objectives
- To analyze the urban expansion of Tehran across different time periods.
- To classify land cover changes (e.g., built-up areas, vegetation, barren land, water bodies).
- To generate change detection maps to visualize the spatiotemporal dynamics of urban growth.
- To provide insights into the environmental and infrastructural impacts of rapid urbanization.

## 🛠️ Technologies & Tools Used
*(نکته: این بخش را بر اساس ابزارهایی که واقعا استفاده کردید تغییر دهید)*
- **Programming Language:** Python
- **GIS & Remote Sensing Libraries:** Google Earth Engine (GEE), Geopandas, Rasterio, GDAL
- **Data Analysis & Visualization:** Pandas, NumPy, Matplotlib, Folium
- **Machine Learning (Optional):** Scikit-learn, TensorFlow (for image classification)

## 📊 Data Sources
*(نکته: اگر از دیتاست خاصی استفاده کردید، اینجا بنویسید. مثلا لندست)*
- Landsat Satellite Imagery (e.g., Landsat 5, 8) 
- Sentinel-2 Imagery
- OpenStreetMap (OSM) Data

## 🚀 Methodology
1. **Data Acquisition:** Collecting multi-temporal satellite imagery for the study area (Tehran).
2. **Preprocessing:** Cloud masking, atmospheric correction, and image co-registration.
3. **Classification:** Applying image classification algorithms to categorize land cover types.
4. **Change Detection:** Using post-classification comparison or image differencing techniques to identify changes.
5. **Analysis & Visualization:** Generating maps and statistical reports to analyze the urban growth trends.

## 📁 Project Structure
*(نکته: ساختار پوشه‌های پروژه خود را اینجا بنویسید)*
- `/data`: Raw and processed datasets.
- `/notebooks`: Jupyter notebooks for data exploration and modeling.
- `/src`: Source code for processing and analysis.
- `/results`: Output maps, charts, and final reports.

## 💻 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
