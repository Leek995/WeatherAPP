# :sunny: [WeatherMap](#3f87a6) :world_map: 

### Description

**WeatherMap** is an application that gathers weather data from all over the world in a format that is easy to read, control, and adjust courtesy of the collaboration of Map Box and OpenWeather API. At the fingertips of the users are a variety of options to find the desired location's weather. One of the most impressive features is a 3D globe with zoomable options that converts  to an 2D format. The map is equipped with a marker to capture precise coordinates. The user also has the ability to traverse the globe using search functionality. Once the user has decided on their location they will be provided with weather data from OpenWeather’s API in said area simultaneously.

### Technologies
The **Front-End Technologies** that make all the magic  possible are *JavaScript* which enables the responsiveness of features like rendering of data asynchronously, and *JQuery* for efficient traversal around the application and as well as within *Map Box* and *OpenWeather API*. The User Interface foundation utilize *Bootstrap5* for its *grid system* allowing precise positioning of the data onto the page. Lastly, *CSS4* which makes the application unique in its own merit improving user experience tremendously.

The **Back-End Technologies** relies heavily on the data from the *REST API's* for it's capability. The data captured is given in real-time and not stored at a specific location.

### Access
Below is a link to a **video demo** that walks through the functionality of the application.
[Click here](https://capture.dropbox.com/FCBxVEf0Q1klHDay)

To view the application and it's source code on your local device. You will need to clone the repo by following the directions below. WeatherMap uses two API's. Therefore, two API key's are needed from both [Map Box](https://docs.mapbox.com/help/getting-started/access-tokens/) & [OpenWeather](https://openweathermap.org/appid) to access the application.
- Copy SSH key by clicking the green drop down button titled, code.
- Type ```git clone``` and paste key into working directory in terminal.
- Insert keys directly into main js file by replacing constant variables named token.
- Run the application through browser.

### Instructions
1. Once the map loads, find the blue marker/pin on the map.
2. Swing the globe in any direction.
3. Drag the marker to the desired proximity.
4. Either zoom in by utilizing the mouse/mousepad for more precision. 
5. The second option to zoom is by using the map control on the physical map.
6. If the location is known, you can also search for destination by using the search bar at the bottom of the map.

### Next version
1. Add the geolocator to the physical map. 
2. Integrate the marker and geolocator with the map.
3. Remove the search bar and utilize the API search functioanilty for the cosmetic abilitiy to include on the map.
4. Re-size the Map. 
5. Include browser geolocation to set default map location.
6. Display a drop-down modal for the default map location forecast.

###### Bugs
- Search functionality works after drag event is triggered. Current Work around is to convert custom seach functionality to geolocator.



