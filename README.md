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
 
 Output 1
![Screenshot 2021-09-19 _deli_2](https://user-images.githubusercontent.com/85843030/133938477-c5afd18b-c7f8-4ebc-8196-70526452fb7e.png)
 

Output 2
![Screenshot 2021-09-19 _deli_2](https://user-images.githubusercontent.com/85843030/133938511-8a8c227e-bf0f-476a-a95d-16b212c7bb81.png)


![Screenshot 2021-09-19_deli2](https://user-images.githubusercontent.com/85843030/133938531-2275518c-c615-4b0f-aba2-882b01b96659.png)



Output 3 & 4
![Screenshot 2021-09-19_deliv_3](https://user-images.githubusercontent.com/85843030/133938542-fb48f2b2-fa01-4212-ade0-d45c8bb58dc8.png)

![Screenshot 2021-09-19_deliv3](https://user-images.githubusercontent.com/85843030/133938554-63d5059a-52f0-4ec9-b5b3-344d51ae7ffe.png)




