# ndvistats
Jupyter Notebook with flow calculation of zonal statistics for selected polygons using geopandas, google earth engine api, rasterio, rasterstats and folium.

The purpose of the code is to apply operations on vectors and raster data using python, and drawing figures in QGIS.

Find invalid geometries in the polygons_test.GeoJSON file. Propose a correction method in python and apply it; Calculate the area of ​​the polygons in hectares; Using the UC layer, obtain for each polygon if there is an intersection with any UC. Calculate the intersect area and obtain the name of the UC corresponding to each polygon; Download the last 5 Sentinel-2 image dates (without cloud), calculate NDVI and crop the images using the polygons obtained in the previous item. Calculate zonal statistics of mean, minimum, maximum and standard deviation of NDVI for each image. Generate cropped NDVI maps for each Sentinel-2 image date. Preferably use QGIS map-composer.
