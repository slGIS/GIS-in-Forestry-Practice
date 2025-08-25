# 🌲 GIS-in-Forestry-Practice

A collection of tools, workflows, and examples demonstrating how **Geographic Information Systems (GIS)** can be applied in forestry for **sustainable management, research, and decision-making**.

This repository provides **practical, reproducible** GIS techniques using open-source tools and data.

---

## ✨ Features

- **Forest Inventory & Mapping**  
  Create detailed maps of forest stands and resources.

- **📊 Data Analysis**  
  Calculate forest area and canopy cover.

## 🛠 Technologies

- **Desktop GIS:** ArcGIS, R-Studio
- **Libraries:** GDAL/OGR, Python (`geopandas`, `rasterio`, `shapely`)  
- **Data:** Open geospatial datasets ( LiDAR, GPS Coordinates )

---

## 📝 Description
Trees with very large crown areas are very few, and most of the trees fall into the smaller crown areas.  
That is why the mean crown area and the mean crown diameter are also small.  

Applying different segmentation algorithms on tree crown polygons, the result was the best fitting segmentation algorithm for the above set of trees is **li2012**.  
After trying out multiple values for the window size, the resulting conclusion was that with assigning a minimum height value of **15** and window sizes from **5 to 11**, we get segmentation results that fit tree crown polygons.  
![LAGHARI](https://github.com/user-attachments/assets/1da379a9-0469-491d-8be5-b571ab729fcb)

---

![LAGHARI (1)](https://github.com/user-attachments/assets/7ff3e0b1-c053-4fc1-8c11-97564f3e6be2)

