---
sectionid: data 
sectionclass: h1
is-parent: yes
title: Data
number: 3000
---

During this workshop we will use different types of data files, including CSV, Geojson, ESRI Shapefiles, and Geotiffs that will help us to work with different types of geospatial features including points, polygons, and raster images.

You will get a basic understanding of these types of different data, specifically how they are created, how they can be mapped, and how they can interact with one another.

Smaller files have been placed in a GitHub repo. Larger Geotiffs (historical maps) have been placed in a Google Drive.

**CSV**

CSV files are your friends. They can be used in virtually every type of tool or software. For mapping purposes they only need to contain two types of information in order to be used: 
1. Latitude and Longitude coordinates allow an individual record to be located on a map as a point. Latitude and Longitude can be generated through the process of geocoding. Geocoding can be an automated process if your CSV records have known addresses. If not, you can manually add latitude and longitude. For historical research the process can often times be both automated and then manually checked to ensure that the locations are accurate. 
2. You do not need to have latitude and longitude data in a CSV file in order to visualize data on a map. If you have a column that contains geographic information, for example a census tract or a neighborhood, and you also have a corresponding data layer of that census tract or neighborhood then you can join your CSV file to that other file and visualize your data within the stated boundary.  

CSV files with locations of places listed in the GreenBook. Special thanks to Professor Genevieve Carpio at UCLA and student research assistant Jose Cardona for creating and sharing the data. Jose Cardona compiled the data for these two CSV files. We used google sheets to store the data and a script that plugs into google sheets to geocode the addresses. Each address was manually transcribed by Jose from the NYPL GreenBook website - https://digitalcollections.nypl.org/collections/the-green-book#/?tab=about - then checked against current street data to verify each location.  

CSV files that we will be using:
1. Greenbook1939
2. Greenbook1947

**Geojson**

Geojson are also your friend! [Geojson is an open standard](https://en.wikipedia.org/wiki/GeoJSON) that displays different types of features. For this workshop we will be working with polygon boundaries in order to show neighborhoods and other distinct geographic areas. The HOLC_LosAngeles.geojson files is a geojson file which is a geographic encoding format. 

Geojson files that we will be using:


**ESRI Shapefile**

ESRI Shapefiles are a propreity format that primarily work with ArcGIS but can also be used in different software including QGIS and CARTO. For this workshop we will work with one ESRI Shapefile in order to see the difference between it and an Geojson file. The biggest difference being that a shapefile is comprised of multiple files instead of just one file. This poses some challenges and 
The la_county-neigbhorhoods-v6.zip file contains a shapefile, which is a vector data format developed by ESRI. The shapefile format requires specialized software to be opened. CARTO allows for shapefiles (up to a certain size) to be uploaded as long as they are zipped. 

ESRI Shapefile that we will be using:


**Geotiffs**

Geotiffs are amazing, espeically for humanities oriented spatial research. A geotiff is an image file that has been georeferenced using GIS software such as ArcGIS or QGIS. Georeferencing or georectifying an image means that the image has had control points assigned to it so that it can be placed into a specific geographic location by software, such as MapBox. We will be working with Geotiffs and we will not be georeferencing any images. 

Geotiffs are usually larger files and because of this you will need to access them via a Google Drive. 

Geotiffs:
1.
2.

Resources:
1. LA Times article using Watts Map - http://graphics.latimes.com/watts-riots-1965-map/
2. Richmond Panoroma project - https://dsl.richmond.edu/panorama/redlining/#loc=9/34.0050/-118.1565&opacity=0.8&city=los-angeles-ca
3. QGIS tutorial for georeferencing - https://docs.qgis.org/2.18/en/docs/training_manual/forestry/map_georeferencing.html

