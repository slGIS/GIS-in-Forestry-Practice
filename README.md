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

![LAGHARI](https://github.com/user-attachments/assets/1da379a9-0469-491d-8be5-b571ab729fcb)
## 📝 Description

Trees with very large crown areas are very few, and most of the trees fall into the smaller crown areas.  
That is why the mean crown area and the mean crown diameter are also small.  
Applying different segmentation algorithms on tree crown polygons, the result was the best fitting segmentation algorithm for the above set of trees is li2012.  
After trying out multiple values for the window size, the resulting conclusion was that with assigning a minimum height value of 15 and window sizes from 5 to 11, we get segmentation results that fit tree crown polygons
---
---

![LAGHARI (1)](https://github.com/user-attachments/assets/7ff3e0b1-c053-4fc1-8c11-97564f3e6be2)
# 📡 GPS Accuracy Evaluation – Strzelna Forest, Poland
## 📝 Description
In our research, we evaluated the accuracy of two different types of GPS devices. One was a professional-grade GPS known as Stonex, and the other was a standard GPS integrated into a mobile phone. Our goal was to determine how closely the coordinates from these devices matched the actual ground positions. We used 40 fixed reference points for our test, each carefully measured using a theodolite, which is a traditional and reliable survey instrument. The positions were recorded in the PL-1992 coordinate system (EPSG:2180), which uses meters. GPS data were then collected from both the Stonex unit and the mobile phone at each reference point.  

Our findings revealed that the Stonex GPS delivered high accuracy. Most of its positional errors were under 1 meter. Its root mean square error (RMSE) was just 0.29 meters, with individual errors ranging from 0.05 to 0.82 meters. This level of precision makes the Stonex GPS ideal for forest surveys and fieldwork where pinpoint accuracy is necessary.  

In contrast, the GPS in the mobile phone showed much lower accuracy. Its errors ranged between 2.27 and 89.83 meters. The RMSE was 25.77 meters, which is significantly higher. The mobile GPS struggled more in forested areas due to signal interference from trees. We also documented the vegetation at each point with photos, helping us link GPS accuracy to environmental conditions. This study confirms that professional GPS devices significantly outperform mobile phone GPS for tasks where accuracy is critical.  

