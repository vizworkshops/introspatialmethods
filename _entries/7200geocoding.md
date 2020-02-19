---
sectionid: Geocoding
sectionclass: h2
parent-id: QGIS Walkthrough
is-parent: yes
number: 7200
title: Geocoding
---

Geocoding is the process of adding latitude and longitude data by using a known address. This is especially useful when you have lots of addresses that need to be processed. One of the challenges for using this process is when your addresses are historical. In this case you must develop a way to check the addresses and ensure that they are accurate. Accuracy in this context is also up for intrepretation. Sometimes you only need to know the general area for an address location. Othertimes you need to have a more precise location. Consider your research and what you are trying to communicate as you determine your level of accuracy. 

Geocoding can be done in numerous ways. ArcGIS and other GIS software may provide geocoding services that your institution has included within their software subscription. Google provides free geocoding services that are limited by how many addresses you can geocode a day. Google sheets has an Add-on called Geocode by Awesome Table that utilizes Google's service to retrieve latitude and longitude data.

Another way to get access to Google's service is by inserting a script into your Google Sheet script editor. For example Github user Max Vilimpoc wrote [this script](https://github.com/nuket/google-sheets-geocoding-macro/blob/master/Code.gs) that can be inserted into your own sheet in order to geocode addresses. 

