# Mapping_Earthquakes
Using the Leaflet.js Application Programming Interface (API) to populate a geographical map with GeoJSON earthquake data from a URL. This interactive map will show each earthquake that occurred in the past seven days and will be visually represented by a circle and color, where a higher magnitude will have a larger diameter and be darker in color. In addition, each earthquake will have a popup marker that, when clicked, will show the magnitude and location of the earthquake.

## Overview of the Project
Basil and Sadhana like how the original earthquake map was created with two different maps (Streets and Satellite) and includes the Earthquake overlay.

Here is the original Street map showing the Earthquake data:

![Streets_original](https://user-images.githubusercontent.com/94148420/159166392-9f98ba94-b6a2-401a-875f-1cd9b0a8a234.PNG)

Here is the original Satellite map displaying the Earthquake data:

![Satellite_original](https://user-images.githubusercontent.com/94148420/159166432-1b76a0f9-7742-43c9-a82b-bbdaaea51145.PNG)

Now, Basil and Sadhana would like to see the interactive map updated to include:

1. Earthquake data in relation to the tectonic plates’ location on the earth
2. Display all the earthquakes with a magnitude greater than 4.5
3. Show the data on a third map *style*, which will be **Dark**.

### Resources
**Code:**
* challenge_logic.js
* index.html

**Data:**
* https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
* https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson

**Software/Data Tools:**
* JavaScript
* Leaflet.js
* GeoJSON
* CSS
* HTML
* Chrome Developer Tools
* Visual Studio Code 1.65.1
* GitHub


## Results
The following are the three interactive map updates that Basil and Sadhana had requested.

### Deliverable 1: Add Tectonic Plate Data
Tectonic plate code is added to challenge_logic.js:

![tectonic_layer](https://user-images.githubusercontent.com/94148420/159167837-4681762c-df24-4bf0-9ee1-73ad48c0553a.PNG)

![tectonic_overlay_object](https://user-images.githubusercontent.com/94148420/159167894-a902c454-ab1e-4b28-a639-f958728636e5.PNG)

![tectonic_plate_call](https://user-images.githubusercontent.com/94148420/159167958-3090954e-6a7a-4614-aed2-294d9736e763.PNG)

Resulting in this *Street* interactive webpage image without Earthquake data:

![tectonic_streets_withoutEQ](https://user-images.githubusercontent.com/94148420/159168106-65619c6c-f7e5-45a5-ac09-3dbed885d737.PNG)

And here is the resulting *Satellite* interactive webpage with Earthquake data:

![image](https://user-images.githubusercontent.com/94148420/159168197-2ed04225-0428-455e-b194-bbe20f9e6eac.png)

### Deliverable 2: Add Major Earthquake Data
Major earthquake code is added to challenge_logic.js:

![majorEQ_layer](https://user-images.githubusercontent.com/94148420/159168326-bd428f8c-44de-4bd0-a24b-97ee7367a630.PNG)

![majorEQ_overlay_object](https://user-images.githubusercontent.com/94148420/159168372-2e6083d2-6a81-422d-a6ac-0cfa20d855ea.PNG)

![majorEQ_code1](https://user-images.githubusercontent.com/94148420/159168536-bdade35a-b03c-4b97-8855-f13c6de8a3dd.PNG)

![majorEQ_with_popup_code2](https://user-images.githubusercontent.com/94148420/159168646-7d1f80a3-742f-4cea-b81e-1232003440d8.PNG)

Here is a the *"Street"* webpage with the Major Earthquake data and popup display:

![majorEQ_image_with_popup_street](https://user-images.githubusercontent.com/94148420/159168806-ecf08446-200f-4ec7-b667-91840aea9508.PNG)

And the *"Satellite"* interactive option with the Major Earthquake data and popup display:

![majorEQ_image_with_popup_satellite](https://user-images.githubusercontent.com/94148420/159168909-8793c79d-bc49-4dbf-a31b-4520dfac052e.PNG)

### Deliverable 3: Add an Additional Map











## Summary
