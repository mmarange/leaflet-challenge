# Leaflet Homework - Visualizing Data with Leaflet

## Background



Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. As a new hire, you will be helping them out with an exciting new project!

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

### Methodology

1. The USGS request has been addressed in two parts found in the follwing folders;  directory for the Leaflet challenge. Use the folder names to  **Leaflet-Step-1** and **Leaflet-Step-2**.



### Level 1: Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

Your first task is to visualize an earthquake data set.

1. **Data Sources**

   ![3-Data](Images/3-Data.png)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes on [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) 
   Here a data set to visualize was picked and called in json format. 

   ![4-JSON](Images/4-JSON.png)

2. **Visualize the Data**

   A map was created using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

   * Data markers reflect the magnitude of the earthquake by their size and and depth of the earth quake by color. Earthquakes with higher magnitudes appear larger and earthquakes with greater depth appear darker in color.

   * **HINT** the depth of the earth can be found as the third coordinate for each earthquake.

   * Popups that provide additional information about the earthquake when a marker is clicked were included.

   * A legend that will provide context for your map data was created.

   

- - -

### Level 2: More Data

![5-Advanced](Images/5-Advanced.png)

The USGS wants you to plot a second data set on your map to illustrate the relationship between tectonic plates and seismic activity.  Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

In this step..

* A second data set on the map was plotted.

* A number of base maps to choose from as well as separate out the two different data sets into overlays that can be turned on and off independently was added.

* A layer controls to our map was added.

- - -



![1-Logo](Images/1-Logo.png)

### Copyright

Data Boot Camp © 2021. All Rights Reserved.