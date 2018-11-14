Udacity Frontend Nanodegree Neighborhood Map
=========================================
### **Overview**
This is a Neighborhood Map project that shows places in one of my favorite neighborhoods in Chicago - Wicker Park. This project utilizes Google Map and Foursquare APIs.

A single-page web application featuring a Google Map of Wicker Park neighborhood in Chicago.
Application functionalities include map markers to identify locations, a search function to easily discover these locations, a list view to support simple browsing of all locations and when selected, additional information about a location is presented from the FourSquare API.
Technologies used: HTML5, CSS, KnockoutJS, Bootstrap, AJAX, Google Map and Foursquare APIs.


### **Usage**
- Use the app [here](https://wioletag.github.io/frontend-nanodegree-neighborhood-map/index.html).
- Or clone or download this repository.
  * Open up a terminal and type following commands to set up a local HTTP Server:
    ```
    cd /home/somedir
    python -m SimpleHTTPServer 8080
    ```
    /home/somedir is the directory of downloaded/cloned project with index.html page.
  * Open a browser and type the following address:
    ```
    localhost:8080
    ```

### **Search input filters**
Search input field has following filters:
- It filters the map markers and list items to locations matching the text input or selection.
- It also filters the map markers and list items based on following key words: bar, food, restaurant, bakery, cafe.
