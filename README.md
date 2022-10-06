## Mapping_Earthquakes

### Project Overview:

The purpose of this project was to illustrate the difference in magnitudes of earthquakes worldwide for the previous seven days. A script was created to extract the GeoJSON earthquake data from the U.S. Geological Survey website, which provided the geographical coordinates and magnitudes of the previous week’s earthquakes. This data was then added to a map (see images below). Since the information is linked to a real-time source, the map updates whenever the user accesses it. Scripts were built using JavaScript and D3.js library to obtain the coordinates and magnitudes of the earthquakes from the GeoJSON data. Then Leaflet library was used to plot the data on a Mapbox style map through an API request and made it interactive by adding visualization for different map styles. The images below display tectonic plates, earthquake magnitudes and location information.

Image 1: Tectonic Plates

![image](https://user-images.githubusercontent.com/109227896/194380505-d56bee98-56f3-4263-8273-6da4f88eee42.png)


Image 2: Major Earthquakes Added (Satellite View)

![image](https://user-images.githubusercontent.com/109227896/194380583-233c1bb8-ecaf-4ec6-9f2f-a885b1564293.png)


Image 3: All Earthquakes Shown (Dark View)

![image](https://user-images.githubusercontent.com/109227896/194380618-0629276f-d347-4163-b821-964275addfe4.png)
