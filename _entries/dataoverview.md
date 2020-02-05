---
sectionid: data overview
sectionclass: h1
is-parent: yes
title: Data Overview
number: 3000
---

Data is critical to GIS and mapping. There is an incredily rich and diverse world of geospatial data.

Geospatial data is broken up primarily into two worlds:

+ Raster
+ Vector

Raster data is basically an image file which contains pixels that displays your data. Raster data can be satellite imagery, it can be a digital elevation models (DEM), or an image file like a TIFF. Raster data lends itself well to representing the physical world.  

  
 | 
**Raster grid showing pixels** | **Raster showing elevation in Los Angeles**
- | -
![Example of a raster grid showing pixels - ](https://raw.githubusercontent.com/vkcworkshops/introspatialmethods/gh-pages/img/rasterdata.png) | ![A raster image showing elevation in Los Angeles - ](https://raw.githubusercontent.com/vkcworkshops/introspatialmethods/gh-pages/img/rasterla.png)

Vector data on the otherhand uses geometry to create points, lines, and polygons. Vector data has geographic data that a GIS can read in order to place it within a map. The data will also have attribute information that describes that data. In the example below street outlines have been created by locating them using geographic information, latitutude and longitude. In addition to that information which results in the creation of lines, additional attribute data provides more information about those lines. In this case the lines are categorized by whether or not they permit dwelling, do not permit dwelling, or do not permit dwelling overnight. 


![Example of vector data maps - ](https://raw.githubusercontent.com/vkcworkshops/introspatialmethods/gh-pages/img/vectordataexample.png){:height="60%" width="60%"}



In addition to these, the most common additional data that is used in GIS is tabular data, such as a CSV or excel spreadsheet. Tabular data can have any number of variables which can be joined to already created vector data. For example, if you had additional data about the number of dwellings on each individual street you could "join" that data and then visualize it. 




**Resources:**  
[A gentle introduction in GIS via QGIS](https://docs.qgis.org/3.4/en/docs/gentle_gis_introduction/index.html)  

[QGIS Documentation about rasters](https://docs.qgis.org/2.8/en/docs/gentle_gis_introduction/raster_data.html)



Resources:
1. [LA Times article using Watts Map](http://graphics.latimes.com/watts-riots-1965-map/)
2. [Richmond Panoroma project](https://dsl.richmond.edu/panorama/redlining/#loc=9/34.0050/-118.1565&opacity=0.8&city=los-angeles-ca)
3. [QGIS tutorial for georeferencing](https://docs.qgis.org/2.18/en/docs/training_manual/forestry/map_georeferencing.html)

