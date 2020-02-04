---
sectionid: data 
sectionclass: h1
is-parent: yes
title: Data
number: 3000
---

Data is critical to GIS and mapping.

There is an incredily rich and diverse world of geospatial datateypes. Some of the most common include CSV, Geojson, Shapefiles, and Geotiffs.

Perhaps even more importantly, is understanding what these files can create:
points
lines
polygons
raster images


**CSV**

CSV files are your friends. They can be used in virtually every type of tool or software. For mapping purposes they only need to contain two types of information in order to be used: 
1. Latitude and Longitude coordinates allow an individual record to be located on a map as a point. Latitude and Longitude can be generated through the process of geocoding. Geocoding can be an automated process if your CSV records have known addresses. If not, you can manually add latitude and longitude. For historical research the process can often times be both automated and then manually checked to ensure that the locations are accurate. 
2. You do not need to have latitude and longitude data in a CSV file in order to visualize data on a map. If you have a column that contains geographic information, for example a census tract or a neighborhood, and you also have a corresponding data layer of that census tract or neighborhood then you can join your CSV file to that other file and visualize your data within the stated boundary.  


**Geojson**

**ESRI Shapefile**

ESRI Shapefiles are a propreity format that primarily work with ArcGIS but can also be used in different software including QGIS and CARTO. 

**Geotiffs**

Geotiffs are amazing, espeically for humanities oriented spatial research. A geotiff is an image file that has been georeferenced using GIS software such as ArcGIS or QGIS. Georeferencing or georectifying an image means that the image has had control points assigned to it so that it can be placed into a specific geographic location by software, such as MapBox. 



Resources:
1. [LA Times article using Watts Map](http://graphics.latimes.com/watts-riots-1965-map/)
2. [Richmond Panoroma project](https://dsl.richmond.edu/panorama/redlining/#loc=9/34.0050/-118.1565&opacity=0.8&city=los-angeles-ca)
3. [QGIS tutorial for georeferencing](https://docs.qgis.org/2.18/en/docs/training_manual/forestry/map_georeferencing.html)

