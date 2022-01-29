# Mapping_Earthquakes

## Background 
 I have just landed at a position, 'Data Visualization Specialist' for the Disaster Reporting Network, a non-profit organization that provides data driven story telling on disasters around the world. My mission if I choose to accept it, will be to build insightful data visualizations with interactive features on earthquakes from around the world. Basil, the head of the earthquake diaster response team, believes that this project will be useful for his team which includes reporters and data visualization specialists. He hopes that making earthquake maps informative and easy to use on desktops and mobile phones will generate positive buzz about the disaster reporting network. In my role, I will be supporting website and mobile app development by using the latest earthquake GeoJSOn data from the US Geological Survey website. I will traverse and retrieve the earthquake data using Javascript and D3 and Leaflet libraries and plot the data on a mapbox map through an API request. On the map the magnitude and location of each earthquake will be shown in a popup marker. The diameter of the markers for each earthquake should reflect the magnitude of the earthquake in size and color. Earthquakes with higher magnitudes will appear larger and darker in color with a legend providing the context for the mapped data. Finally to illustrate the relationship between the location and frequency of the seismic activity and tectonic plates we will add fault lines on the map.


## Basic Project Plan

### Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. I will be creating an interactive world map using Javascript and GeoJSON. We will use the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL. Each earthquake will be visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. In addition, each earthquake will have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.

### Tasks
To complete this project, we will use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

### Approach
The approach will be to use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. You'll use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Tools used : 
1. Mapbox API - It provides custom maps for websites and applications such as Strava, Facebook, the Financial Times, The Weather Channel, Snapchat, and Instacart. Since October 2019, Mapbox has been generating up to 14 billion individual sensor readings daily across 100,000 map updates on connected devices.

2. GeoJSON data - It is a type of JavaScript Object Notation (JSON) data that is specifically designed to host geographical information. GeoJSON data consists of a single object, which can be represented by a geometry object, features object, or collection of features (FeatureCollection object). GeoJSON data can be found in many apps that have the mapping feature such as ride sharing, navigation and food and package delivery services. Even the apps on the smartphone that allow to track your location can store and use GeoJSON data. The GeoJSON format is the industry standard for representing simple geographical features and non-spatial attributes. Various geographical features such as the following can be implemented using the GeoJSOn data:
  1. Points - Points contain addresses and locations like latitudes and longitude coordinates.
  2. Linestrings - Linestrings contain coordinates for the boundaries of streets, highways, travel routes and tectonic plates.
  3. Polygons - Polygons contain coordinates for the boundaries of zip codes, counties, countries, provinces and tracts of land. 

We can also represent non-spatial attributes, that is, data that is independent of all geometric considerations and packaged in a hierarchial structure in a GeoJSON file. Examples are elevation, temperature, rain accumulation, hail size, tornado/hurricane strength and magnitude of an earthquake.

3. Using Javascript and D3 library we will traverse and retrieve GeoJson earthquake data and tectonic plate data in order to populate a map. 
4. Leaflet Library - 
The Leaflet CSS and JavaScript files we added to the index.html file are referred to as content delivery networks (CDNs). Using CDNs has a security risk. To avoid the security risk, it's a best practice to include an integrity value with the CDN. Each file we added has its own integrity value, which is a Base64-encoded cryptographic hash of a resource that prevents the CDN from being hacked.
