---
sectionid: data 
sectionclass: h1
is-parent: yes
title: Data
number: 3000
---

Data is critical to GIS and mapping. There is an incredily rich and diverse world of geospatial data.

Geospatial data is broken up primarily into two worlds:

- Raster
- Vector

Raster data is basically an image file which contains pixels that displays your data. Raster data can be satellite imagery, it can be a digital elevation models (DEM), or an image file like a TIFF. Raster data lends itself well to representing the physical world.

![Example of a raster grid showing pixels - ](https://raw.githubusercontent.com/vkcworkshops/introspatialmethods/gh-pages/img/rasterdata.png)
![A raster image showing elevation in Los Angeles - ](https://raw.githubusercontent.com/vkcworkshops/introspatialmethods/gh-pages/img/rasterla.png)

[QGIS Documentation about rasters](https://docs.qgis.org/2.8/en/docs/gentle_gis_introduction/raster_data.html)



Vector data uses geometry to create points, lines, and polygons. 

In addition to these, the most common additional data that is used in GIS is tabular data, such as a CSV or excel spreadsheet. Tabular data can have any number of variables which can be joined to 




**CSV**

CSV files are your friends. They can be used in virtually every type of tool or software. For mapping purposes they only need to contain two types of information in order to be used: 
1. Latitude and Longitude coordinates allow an individual record to be located on a map as a point. Latitude and Longitude can be generated through the process of geocoding. Geocoding can be an automated process if your CSV records have known addresses. If not, you can manually add latitude and longitude. For historical research the process can often times be both automated and then manually checked to ensure that the locations are accurate. 
2. You do not need to have latitude and longitude data in a CSV file in order to visualize data on a map. If you have a column that contains geographic information, for example a census tract or a neighborhood, and you also have a corresponding data layer of that census tract or neighborhood then you can join your CSV file to that other file and visualize your data within the stated boundary.  


**Geojson**

**ESRI Shapefile**

ESRI Shapefiles are a propreity format that primarily work with ArcGIS but can also be used in different software including QGIS and CARTO. 

**Geotiffs**

Geotiffs are amazing, espeically for humanities oriented spatial research. A geotiff is an image file that has been georeferenced using GIS software such as ArcGIS or QGIS. Georeferencing or georectifying an image means that the image has had control points assigned to it so that it can be placed into a specific geographic location by software, such as MapBox. 



https://thetruesize.com/#?borders=1~!MTM3Njc1ODQ.MjA0MjQ4NQ*MjQzMzMxMjE(NjM1MDY5OQ~!GL*MTAyMzA5NTg.MTUyNjUwNA)Mw

Resources:
1. [LA Times article using Watts Map](http://graphics.latimes.com/watts-riots-1965-map/)
2. [Richmond Panoroma project](https://dsl.richmond.edu/panorama/redlining/#loc=9/34.0050/-118.1565&opacity=0.8&city=los-angeles-ca)
3. [QGIS tutorial for georeferencing](https://docs.qgis.org/2.18/en/docs/training_manual/forestry/map_georeferencing.html)

