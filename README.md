# Mapping_Earthquakes
## Purpose
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. The map uses Leaflet and Mapbox to map earthquakes and tectonic plates. It incorporates different layers for interactivity in which the layers can be turned on or off. It also uses different map styles: streets, satellite or dark.

## Tasks
To complete this project, use a URL for GeoJSON earthquake data from the USGS website and retrieve geographical coordinates and the magnitudes of earthquakes for the last seven days. Then add the data to a map.

## Approach
Use the JavaScript and the D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. Use the Leaflet library to plot the data on a Mapbox map through an API request and create interactivity for the earthquake data.

## Results
The results of the analysis show visually appleaing maps that the user can change for different views. The default map is the street view with all earthquakes in the last 7 days and the major earthquakes that are over 4.5 magnitude in the last 7 days from USGS data. 

![Screen Shot 2022-07-09 at 4 10 52 PM](https://user-images.githubusercontent.com/99676466/178124430-53629612-a52f-46c6-97f9-0717d31373ea.png)

The next map style selection is the satellite view. The legend is color coded to show different sizes of earthquakes and there are popups when an earthquake is clicked: 

![Screen Shot 2022-07-09 at 4 25 11 PM](https://user-images.githubusercontent.com/99676466/178124506-77a4eded-fd26-437a-a02e-2295ae11a868.png)


And the third style is the dark view. There were not very many major earthquakes in the last 7 days so that particular layer is not that interesting. 

![Screen Shot 2022-07-09 at 4 11 09 PM](https://user-images.githubusercontent.com/99676466/178124465-880b29bf-0437-4c02-bce3-a143596a76bc.png)

### Tools: 
Javascript, D3, Leaflet, GeoJSON, Mapbox Api, HTML/css, VS Code



