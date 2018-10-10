---
sectionid: mapbox
sectionclass: h1
is-parent: yes
title: Mapbox
number: 5000
---

Mapbox is an open source platform that allows you to design custom maps. If CARTO is an entry level tool for easily creating a fully interactive map in a few minutes, Mapbox is on the other spectrum. You can create fully customizable maps fairly quickly but to make them fully interactive (pop-up windows or widgets etc) it takes time. Mapbox also does not provide access to any spatial tools in its interface. This doesn't mean that you cannot make those types of maps. It just means you will need to learn how to code those yourself. 

The other thing that Mapbox lets you do and the reason why it is a part of this workshop is that you can utilize it as a server to host your own historical map layers (or even image layers). 

We will upload a Geotiff to Mapbox as a tileset, add that tileset to an existing style (really just adding them to a base layer of data, imagine if you opened up Google Maps and you saw a historical map in addition to the current satellite data!).

Mapbox is already fully integrated into platforms such as CARTO and Tableau. What that means is that once you create your style with a historical map you can add it to these platforms with just a simple click of the button. 

We won't stop there though. There are some limitations to this and as part of this workshop we will use MapBox and our data to try and recreate our CARTO maps (in part) as stand alone coded maps. This means we will take our data out of CARTO, put it into Mapbox, and then write (really copy) some code. 

