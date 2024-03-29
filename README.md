# USGS Earthquake Map

You can view the interactive earthquake map here: https://danacw.github.io/USGS-Earthquake-Map/

In this interactive map, users can review earthquake data over a 7-day span with data from the USGS. Earthquake and tectonic plates layers were added to four different overlay maps, to give users the ability to switch between views. Marker size is based on the magnitude of the quake, while marker color is based on its depth. Users have the ability to click on each marker to view data on time, location, and magnitude of each specific quake. 

**Data Sources:**
  - Eathquake GeoJson was provided by the USGS with data updating every hour: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php. 
  - Tectonic plates GeoJSON was provided by Fraxen: https://github.com/fraxen/tectonicplates
  - Overlay maps provided through the Mapbox API : https://docs.mapbox.com/api/maps/ 

**Index.html**
  - The html source that hosts the map.

**Static/js**
  - logic.js: the JavaScript file used to read in my data and build the map.

**Static/css**
  - style.css: the basic styling of my map and legend. 

![Screen Shot 2021-07-26 at 1 13 07 PM](https://user-images.githubusercontent.com/26308909/127052806-353396d2-f473-4d2f-ae1d-76c41d57f3c5.png)
