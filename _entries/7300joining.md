---
sectionid: Spatial Join
sectionclass: h2
parent-id: QGIS Walkthrough
is-parent: yes
number: 7300
title: Spatial Join
---

Spatial joining is the process of joining two different spatial datasets. This can be done in a variety of different ways. For example, you may have a set of boundaries, for example neighborhood boundaries, and a second set of data that you collected about the neighborhood. In order to visualize that data you will need to join it to the boundary file. 

A common useage of spatial joining is downloading census data and then joining to the corresponding geographic boundary - census tract, county, state, etc. 

We will look at joining census data from Social Explorer to census tracts downloaded from the LA County GIS website.  

One of the challenges of joining census data in GIS software is the leading zero problem. Census tract shapefiles usually have a zero appeneded to whatever their value is - "06037911001" whereas the census data downloaded from Social Explorer of government websites will not have the zero - "6037911001". The problem with this is that when you try to join the data you will not be able to as QGIS needs the exact same values to be able to join. This requires you to add a leading zero in Excel before making your join.

[SLIDES showing how to add leading zeros for GEOID](https://slides.com/arutkows/focus-on-qgis/live?context=editing#/4/3)

Resources:

[Very simple discussion about different types of spatial joins from GISGeography](https://gisgeography.com/spatial-join/)
