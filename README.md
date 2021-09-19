# 1.0 Earthquake_Maps
## 1.1 Project Overview
    Earthquake map has been created using data from:
    The aim of this project is to add earthequake data in relation to the tectonic plate's location on earth.
    
    
# 2.0 Resources
- JavaScript, GeoJson & Leaflet libraries
- DevTools
- Mapbox
- Tectonic data obtained from: https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
- Earthquake data obtained from : https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson, and,
  https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

# 3.0 Coding Summary
  For deliverable 1, the tectonic plate data is added to the map as a second layer, and the the tectonic plate data is added to
  the overlay object.
  Using d3.json() retrievs the the data and pass the tectonic data to the geoJSON() layer, which adds color and width (optional) to the tectonic plate lines.
  Color used is red. the tectonic layer group is added to the map. (see output1)
  
  For deliverable 2, continuing using the code from deliverable1, a third layer group is added for the major earthquakes using data from 
  https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson.
  We use functions to get the colors and radiouses of the circle's depending on their magnitude. For this deliverable, the colors for mag>5 &6 is set to red, and 
  the mag<5 to the same range as in the code given, orange. Finaly we add the major earthquake layer group to the map (output 2)
  
  For deliverable 3, using Mapbox styles, a thrid map style is added as a tile layer object, a dark map. (output 3) and (output 4).
  
 # 4.0 Results
 
