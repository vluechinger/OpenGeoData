# OpenGeoData Course FHNW

## Content

This repository contains the demos and exercises as shown in the course OpenGeoData taught by Prof. Martin Christen at the FHNW Switzerland.
The course concerned itself with getting geographical data from various sources using APIs, hereby focusing on Switzerland.

## Sources

Used sources:
- swisstopo: STAC, swissimage, swissALTI3D, swissBoundaries3D
- WMS: web map service
- WMTS: web map tile service
- OWSLib
- AWS cloud datasets, Landsat 8
- CityJSON
- 3D city models
- LiDAR-Data

This data was then analysed and manipulated using Python as well as QGIS.

## Python Libraries

Used Python libraries:
- Folium to get map representations
- Shapely to draw polygons
- Fiona to import and store geodata
- Geopandas to import, store and plot geodata
- Geoplot to (roughly) plot geodata
- Rasterio to cut out segments of the map 
- GDAL (dependency of rasterio)
- skimage (scikit image)
- cjio (CityJSON)

The notebooks also require the access to two python scripts made available by Christen: geopandas_stac and geoutils (in the src folder).
