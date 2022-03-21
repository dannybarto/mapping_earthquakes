# Mapping_Earthquakes

## Purpose

The purpose of this project is to build a map that tracks not only the earthquakes for the past 7 days, but the magnitude as well. The map also includes pop-up information for each incident.

## Project Overview

- Use d3.json() to get tectonic plate data and add the data using the L.geoJSON() layer.
- Style the tectonic plate LineString data to stand out on the map.
- Add the tectonic plate data as an overlay with the earthquake data.
- Add a third map style to allow the user to select from three different maps.




## Resources
- Data Source: [Earthquake Data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson)
- Data Source: [Fault Line Data](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json)
- Software: Visual Studio Code, 1.38.1, JavaScript, HTML5, CSS & D3.js

## Summary

- Access GeoJSON data website <a href="https://vrod237.github.io/Mapping_Earthquakes/">here</a>
- The map displays all earthquake data over the past 7 days and it also shows where all tectonic plates are located around the world.
- By clicking on one of the circles, that represents and earthquake, you can view the magnitude and the location of where the earthquake occurred. 
- You can choose to toggle the map view from 4 different styles: Street View, Satellite View, Light View and Dark View. 
- You can also choose to toggle the earthquake and tectonic plate data, they both are defaulted to appear. <br>
<br><hr><br>![Map_Earthquake_Data](https://github.com/vrod237/Mapping_Earthquakes/blob/master/Misc%20Files/Map.png)
