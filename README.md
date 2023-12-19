# Farming Systems
This Jupyter Notebook script is designed to classify irrigated and rainfed farming systems based on harmonics of the **Normalized Difference Vegetation Index (NDVI, the Land Surface Temperature (LST)** and the **evapotranspiration (ET)**, that work as predictors for a random forest classifier. The algorithm works on a spatial resolution of 10m and uses Sentinel-2 data over a time period of 3 years as input data. The final output classification is then valid for this 3-year time span. 

### **Requirements**
 - System Requirements: Windows 10/11 64 bits, not tested on Linux. 
 - At least 16GB of RAM. 
 - Dependencies: defined in the environment file


### **Input**
Format needs to geotiff and ESRI shapefile.
 - Study area: Shapefile of the Study Area. 
 - Training data: Shapefile containing polygons for irrigated and rainfed cropland.
