# Traffic-hotspot-detection-using-DBSCAN

> Machine learning project to detect traffic accident hotspots using DBSCAN clustering on GIS shapefiles.

## About
This project detects **traffic accident hotspots** by applying the **DBSCAN** clustering algorithm to GIS data. By analyzing accident location data in projected coordinates, it identifies dense clusters that indicate high-risk areas for city planners and public safety agencies.

---

## Features
- Load accident location data from GIS shapefiles
- Clean and preprocess geospatial data
- Transform coordinates if necessary (e.g., to metric projection)
- Cluster using **DBSCAN**
- Automatically detect high-density accident hotspots
- Export results as new shapefiles or CSV
- Visualize hotspots on maps

---

## Data
Example data format:
- ESRI Shapefiles (`.shp`, `.shx`, `.dbf`, etc.)
