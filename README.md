cistern_map
=============

Maps Cisterns in San Francisco using Javascript and Leaflet/MapTiles

The cistern.json files is a GeoJSON file

Part of the WaterWorks project (waterworks.io)

**Known problems:**

(1) Right now cisternjson.js returns a JSON object of a number of cisterns. Right now, this is a literal, just added there. This should be a non-blocking file-loading system.

(2) The left panel isn't set to the correct width & height, resulting in some obvious formatting issues.

(3) The last cistern marker is set by default 

**Future Improvements:**

(1) Title text

(2) Better design/layout: cisterns, custom colors and more

(3) Link back to WaterWorks project

(4) Actual html on left panel instead of sample text

(5) A splash screen for startup

**Local development:**

1. Launch Terminal, cd into the cistern_map directory
2. python -m SimpleHTTPServer
3. In Chrome, go to: http://localhost:8000/

by Scott Kildall
@kildall
