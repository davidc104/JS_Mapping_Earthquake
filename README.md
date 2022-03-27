# JS_Mapping_Earthquake
## Purpose:
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Tasks:
- Use the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from USGS (United States Geological Survey). 
- Retrieve geographical coordinated and the magnitude of the earthquakes for the last seven days
- Add data to map
- Each earthquake will be visually represented by a circle and color, where a higher magnitude will have a larger diameter and will be darker in color. 
- Each earthquake will have a popup marker that, when clicked, will show the magnitude of the earthquake and the location of the earthquake.

## Approach:
- Use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. 
- use the Leaflet library to plot the data on a Mapbox map through an API request 
- Create interactivity for the earthquake data by layering

## Branching:
In addition to Mapping earthquakes, few practice maps were done by creating branches off the main branch

<img width="386" alt="image" src="https://user-images.githubusercontent.com/94877067/160295519-4df3bd49-caa5-49a9-9e52-3de13f6904d5.png">

## Methods and Result:
- Realtime 7 day earthquake JSON data was obtained from the USGS URL using d3.json ()

<img width="437" alt="image" src="https://user-images.githubusercontent.com/94877067/160295770-39cf7d5f-fd41-48b3-b10a-e60c106d6ded.png">

- Magnitide of the earthquake in each location is represented using circle marker 

<img width="420" alt="image" src="https://user-images.githubusercontent.com/94877067/160295895-9f5c24ff-5c48-4e0b-822c-519a897adc83.png">


- The radius of the circle corresponds to the magnitide of the earthquake


<img width="201" alt="image" src="https://user-images.githubusercontent.com/94877067/160295865-5297df73-8824-4015-9c42-e46bf7ed07fd.png">

- The color of the circle marker also corresponds to the range of earthquake magnitude


<img width="379" alt="image" src="https://user-images.githubusercontent.com/94877067/160295971-b335bc1d-2a34-43dd-b06d-69cd274ca282.png">

- The map had 3 tile layer for visulaization - Streets, Satellite and Dark

<img width="745" alt="image" src="https://user-images.githubusercontent.com/94877067/160296017-549bdd96-12c9-4c0a-aa4c-1b30a0ebf553.png">

- In addition to the tile layer, the map has also 3 layers for visualizing the data:
 The general earthquake locations
 
<img width="230" alt="image" src="https://user-images.githubusercontent.com/94877067/160296177-4b829319-ae1a-4934-9dac-1bb478b7e6fb.png">

Tectonic plate's location
<img width="793" alt="image" src="https://user-images.githubusercontent.com/94877067/160296196-cb0449b3-c691-4a6a-acbb-6a708ad536c8.png">

Earthquake data with magnitude greater than 4.5 on the map
<img width="695" alt="image" src="https://user-images.githubusercontent.com/94877067/160296237-3fd786a1-d9f0-4751-99f7-a229c5c92509.png">











