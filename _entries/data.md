---
sectionid: data 
sectionclass: h1
is-parent: yes
title: Data
number: 3000
---

For this project we will use a collection of different types of data:

* points 
* polygons
* raster image

You will get a basic understanding of these types of different data and how they can be mapped.

All files are located in this google drive: 

**https://drive.google.com/drive/folders/1IwftaTkbRf0fxulIwYzKVBQsGgMSuTpe?usp=sharing**

**CSV files (points)**

CSV files with locations of places listed in the GreenBook. Special thanks to Professor Genevieve Carpio at UCLA and student research assistant Jose Cardona for creating and sharing the data. Jose compiled the data for these two sheets last year while doing research for an ongoing project. We used google sheets to store the data and a script that plugs into google sheets to geocode the addresses. Each address was manually transcribed by Jose from the NYPL GreenBook website - https://digitalcollections.nypl.org/collections/the-green-book#/?tab=about - then checked against current street data to verify each location.  
* _[39GreenBook.csv](https://drive.google.com/file/d/1qguhTbuqiL-xjnT2pFXEFtoUd87YUr4J/view?usp=sharing)_
* _[47GreenBook.csv](https://drive.google.com/file/d/1tdhKybt6xm75HLa8VF8yb6hucGfb1II5/view?usp=sharing)_

**Boundary Files (polygons)**
These files show distinct boundaries with associated metadata. The HOLC_LosAngeles.geojson files is a geojson file which is a geographic encoding format. The la_county-neigbhorhoods-v6.zip file contains a shapefile, which is a vector data format developed by ESRI. The shapefile format requires specialized software to be opened. CARTO allows for shapefiles (up to a certain size) to be uploaded as long as they are zipped.  
* _[la-county-neighborhoods-v6.zip](https://drive.google.com/file/d/1WEkqG8312qA_TGKYUU8FO7HvT-uBN_AO/view?usp=sharing)_
Los Angeles Neighborhood boundaries as developed by the LA Times.
* _[HOLC_LosAngeles.geojson](https://drive.google.com/file/d/1j5mW-r4b0A_mU5Zx_UG711LUQuMzF_o5/view?usp=sharing)_ 
Boundaries showing grades for defined neighborhoods in 1939.
* Lots of boundary files provided by the LA Times - http://boundaries.latimes.com/sets/

**Historical Maps (Raster)**
These maps are already geo-referenced. This means that they have been processed using GIS software so that they have been associated or pinned to real world locations. The files are all .tiff files that have been geo-referenced. 
* _[wattsmap.zip](https://drive.google.com/file/d/1FIy-UBg48NLZfYIjiJYTXSHISJpfzGE9/view?usp=sharing)_ 
* 4 HOLC Maps: _[NorthEastLA.zip](https://drive.google.com/file/d/1UbzVqsw4hvJ0r0VwhzC1f-h452c3M5rb/view?usp=sharing), [NorthernLA.zip](https://drive.google.com/file/d/1-D2t0kcxWR-5NqdIlUgM2zh-KIC9Kcd1/view?usp=sharing), [SouthernLA.zip](https://drive.google.com/file/d/1z056PKbMCerAUxqZOcblzDtzwn0wJewB/view?usp=sharing), [CentralLA.zip](https://drive.google.com/file/d/1PVxxh4B0fj08vaoEyye2qWwJsXSWQzKQ/view?usp=sharing)_
* LA Times article using Watts Map - http://graphics.latimes.com/watts-riots-1965-map/
* Richmond Panoroma project - https://dsl.richmond.edu/panorama/redlining/#loc=9/34.0050/-118.1565&opacity=0.8&city=los-angeles-ca
* QGIS tutorial for georeferencing - https://docs.qgis.org/2.18/en/docs/training_manual/forestry/map_georeferencing.html

