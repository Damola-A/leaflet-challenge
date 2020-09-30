# Leaflet Homework - Visualizing Data with Leaflet

<img src="app.png" height="500" width="1200" />

### Project Description

The goal of the project is to display multiple and interactive maps with the location and magnitude of earthquakes around the world. Javascript, HTML, CSS, Bootstrap were used in the project. The Mapbox-API was also used to load the base maps. The project was divided into two steps with different levels of complexity.

### Step 1: Basic Visualization

A single base layer and one set of data were used:
   * Base layer: https://docs.mapbox.com/api/maps/#raster-tiles
   
   * Data layer Source and Data:
        - Source: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php (United States Geological Survey (USGS))
        - Data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
        
 ### Step 1: More Data

Multiple optional and interactive base layers were included. An additional dataset and plot were included and they can be activated and deactivated by the user.
   * Base layer: 
       - https://docs.mapbox.com/api/maps/ (id: 'mapbox.high-contrast', id: 'mapbox.streets', 'mapbox.dark', 'mapbox.satellite')
       
   * Data layer Source and Data:
       - Layer 1 Earthquake information
            * Source: https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php (United States Geological Survey (USGS))
            * Data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
       - Layer 1 Tectonic Plates
            * Source: <https://github.com/fraxen/tectonicplates>
            * Data: https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json



