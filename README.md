# leaflet-challenge

![1-Logo](https://user-images.githubusercontent.com/117672086/235572896-064d4486-37a6-4b84-a90d-d49a27098f1b.png)

![2-BasicMap](https://user-images.githubusercontent.com/117672086/235572926-c519b832-e940-4b6c-9e34-8638d0e2b2a2.png)

![3-Data](https://user-images.githubusercontent.com/117672086/235572929-6fcc6913-6a48-4b39-b890-7cb229fa3acb.png)

![4-JSON](https://user-images.githubusercontent.com/117672086/235572931-311e17ad-ce88-4be8-bccf-5a5e8319b732.png)

![5-Advanced](https://user-images.githubusercontent.com/117672086/235572932-5b35c103-8796-456e-a4ef-92d525bf0d94.png)

![6-Time_Keeps_On_Ticking](https://user-images.githubusercontent.com/117672086/235572934-66b80034-d268-4f44-b99f-96763b0bb086.gif)

![Cluster](https://user-images.githubusercontent.com/117672086/235572940-1daf10d2-6f02-499c-b887-0c7e81d1d552.png)

![Heat](https://user-images.githubusercontent.com/117672086/235572943-fe073ea8-fb4e-43d0-b117-615cc1de48ee.png)

Part 1: Create the Earthquake Visualization

Your first task is to visualize an earthquake dataset. Complete the following steps:

Get your dataset. To do so, follow these steps:

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the USGS GeoJSON FeedLinks to an external site. page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:

When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:


Import and visualize the data by doing the following:

Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.

Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

Hint: The depth of the earth can be found as the third coordinate for each earthquake.

Include popups that provide additional information about the earthquake when its associated marker is clicked.

Create a legend that will provide context for your map data.

Your visualization should look something like the preceding map.


#Part 2: Gather and Plot More Data (Optional with no extra points earning)

Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at https://github.com/fraxen/tectonicplatesLinks to an external site..

This part is completely optional; you can complete this part as a way to challenge yourself and boost your new skills.

Perform the following tasks:

Plot the tectonic plates dataset on the map in addition to the earthquakes.

Add other base maps to choose from.

Put each dataset into separate overlays that can be turned on and off independently.

Add layer controls to your map.
