# Mapping_Earthquakes

## Purpose
The purpose of this analysis is to create an interactive map web page that shows earthquakes, tectonic plates and major earthquakes, those over magnitude 4.5, on one of three maps chosen by the user.

## Resources
The following data files are used
1. https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
2. https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
3. https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

### Tools
Software: JavaScript, HTML, CSS
Libraries: D3, Mapbox, Leaflet

## Product Creation Overview
The web page was was created and is shown via HTML and css. Javascript was used along with d3, mapbox andLeaflet to create the functionality that shows selectable three maps that are available in the top right
selection box, Figure 1.

![](https://github.com/davidmcbee/Mapping_Earthquakes/blob/master/Earthquake_Challenge/static/images/SelectionBox.png).

Figure 1.
The available maps are the street view, the satellite view and the dark view. The overlays reapresent all earthquakes worldwide, techonic plates and major earthquakes, those greater than 4.5 magnitude over the last week.
### Product Images
Figure 2 is the street map view showing all earthquakes along with a popup indicating maginitude and loaction.

![](https://github.com/davidmcbee/Mapping_Earthquakes/blob/master/Earthquake_Challenge/static/images/EarthquakesMap_street.png)

Figure 2.

Figure 3 is the street view map showing the techtonic plates in addition to all earthquakes. Note the popup indicating the name of the techtonic plate.

![](https://github.com/davidmcbee/Mapping_Earthquakes/blob/master/Earthquake_Challenge/static/images/EarthquakesMap_TechonicPlates_street.png)

Figure 3.

Figure 4 introduces major earthquakes along with all earthquakes and techtonic plates. In addition to the pop up indicating the magnitude and location, the circle sizes represent the magnitudes, just like all earthquakes.

![](https://github.com/davidmcbee/Mapping_Earthquakes/blob/master/Earthquake_Challenge/static/images/EarthquakesMap_MajorQuakes_street.png)

Figure 4.

Figure 5 shows all three overalays on a satellite map.

![](https://github.com/davidmcbee/Mapping_Earthquakes/blob/master/Earthquake_Challenge/static/images/Earthquakes_Satellite.png)

Figure 5.

Figure 6 shows all three overlays on a dark map.

![](https://github.com/davidmcbee/Mapping_Earthquakes/blob/master/Earthquake_Challenge/static/images/Earthquakes_Dark.png)

Figure 6.

Finally the selection box is shown in the upper right corner in Figure 7. this is where the user can select one of the three maps and one, two or all three overalys.

![](https://github.com/davidmcbee/Mapping_Earthquakes/blob/master/Earthquake_Challenge/static/images/Earthquakes_control.png)

Figure 7.
